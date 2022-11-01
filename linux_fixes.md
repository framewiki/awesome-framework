# Linux Tips

UNDER CONSTRUCTION!!!

## Common issues

Changing Screen Brightness via keyboard does not work:
Due to the ambient light sensor not working please do the follwing

Add the fallowing to this file: 
```shell 
sudo nano /etc/modprobe.d/framework-als-deactivate.conf
```

```shell
blacklist hid_sensor_hub
```

### KDE Plasma Tips

Right Click Fix
For KDE the current fix is to use double taping and the following will show you how to enable that.
1. Go to Setting -> Imput Devices -> Trackpad -> Enable Tap to Click

### Gnome Tips

COMMING SOON


## How to Improve Battery Life On linux

Packages nessarry to Improve battery Live:
- Powertop
- TLP

Highly recommened for improved battery life:

- TKG kernel

Why should I Build the TKG kernel:
Comming soon

Build a TKG kernel:
#### Arch & derivatives
```shell
git clone https://github.com/Frogging-Family/linux-tkg.git
cd linux-tkg
# Optional: edit the "customization.cfg" file
makepkg -si
```

#### DEB (Debian, Ubuntu and derivatives) and RPM (Fedora, SUSE and derivatives) based distributions
```shell
git clone https://github.com/Frogging-Family/linux-tkg.git
cd linux-tkg
# Optional: edit the "customization.cfg" file
./install.sh install
```


#### Recommended settings:
1. Will ask you for what kernel you want to build from 1-5
  a. For latest kernel cho0se option 0
  b. For latest stable kernel choose option 1 (Reccomended)
  c. For latest LTS kernel choose option 2
2. Will ask you for whitch CPU sched variant 
  a. For best bettery life choose option 2
3. Ask you for what comilar you want to use to build the kernel 
  a. Go with 0 as its the recommended option
4. Will dowload the kernel that is needed and install the nessarry packages alongside the nessarry patches
5. Will ask you for what CPU architecture you want
  a. 11th gen CPU's option 41 rapterlake
  b. 12th gen CPU's option 42 alderlake
6. Will ask you what kernel interrupt timer frequency would you like to use
  a. For Framework laptops its best to use option 2 300MHz
7. Will ask you if you want to use periodic ticks or full tickless or idle tickles
  a. For us its best to pick option 1 the full tickless
8. Will ask you ACS override patch
  a. For most people just type n
9. Will ask you if you want to enable android modules for Andbox
   a. For Most peaople just hit n
10. If you want to fully pick and choose everything you want to be in the kernel
  a. If you dont want to configure everyting just hit enter which will just do the default options
  b. More comming Soon
11. Now the kernel will compile which will take a little while so take a rest while you wait
  a. Depending on what you picked it could take 15 mins - 60 mins or longer depending on what you picked
12. Script should automatically install the kernel for you inside the boot folder
13. REQUIRED!!!! Configure grub menu to include the new kernel
  a. Easiest Method: Install the grub-customizer
  b. You should have your newly made kernels listed
  c. Now you can click on your new kernel and hit the up arrow to set it as the first option to boot with and save it
  d. Now restart your system and enjoy your new kernel
