# motionpi-config #

### Description ###

* my motionpi server configuration for raspberry pi 3
* installs and runs the following docker containers:
	* [portainer](https://hub.docker.com/r/hypriot/rpi-portainer)
	* [motioneye](https://hub.docker.com/r/vividboarder/rpi-motioneye)
	* [letsencrypt](https://hub.docker.com/r/lsioarmhf/letsencrypt)

### Usage ###

```bash
git clone git@github.com:klutchell/motionpi-config.git ~/motionpi
sudo ~/motionpi/bin/install
sudo ~/motionpi/bin/configure
~/motionpi/bin/pull
~/motionpi/bin/up
```

### Contributing ###

* n/a

### Author ###

* Kyle Harding <kylemharding@gmail.com>
