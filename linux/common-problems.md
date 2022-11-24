[Home](/README.md)
# Common Problems on Linux
## Contents
- [Brightness Keys Do Not Work](#brightness-keys-do-not-work)

## Brightness Keys Do Not Work:
The ambient light sensor takes over control of the screen brightness, preventing the keys from working. To fix this, create a file called `/etc/modprobe.d/framework-als-deactivate.conf` and add the following text to it:
```shell
blacklist hid_sensor_hub
```

<details>
<summary><b>DISCLAIMER</b></summary>
This repository and the resources within it are <b>COMPLETELY UNOFFICIAL</b> and not in any way endorsed or supported by Framework. Your use of these guides and projects is <b>AT YOUR OWN RISK</b> and <b>MAY VOID YOUR WARRANTY.</b> We ask that you do not reach out to Framework support about problems related to these resources, but you can feel free to reach out to the community maintainers via GitHub Discussions or Issues within this repository.
</details>
