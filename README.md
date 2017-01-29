# Docker Motion Server #

## Description ##

This is a docker-based motioneye server for rasbian using pre-built public images.
It pulls and runs the following docker images via [docker-compose](https://github.com/docker/compose):

Image | Size | Version
--- | --- | ---
[hypriot/rpi-portainer](https://hub.docker.com/r/hypriot/rpi-portainer) | [![](https://images.microbadger.com/badges/image/hypriot/rpi-portainer.svg)](https://microbadger.com/images/hypriot/rpi-portainer) | [![](https://images.microbadger.com/badges/version/hypriot/rpi-portainer.svg)](https://microbadger.com/images/hypriot/rpi-portainer)
[vividboarder/rpi-motioneye](https://hub.docker.com/r/vividboarder/rpi-motioneye) | [![](https://images.microbadger.com/badges/image/vividboarder/rpi-motioneye.svg)](https://microbadger.com/images/vividboarder/rpi-motioneye) | [![](https://images.microbadger.com/badges/version/vividboarder/rpi-motioneye.svg)](https://microbadger.com/images/vividboarder/rpi-motioneye)
[lsioarmhf/letsencrypt](https://hub.docker.com/r/lsioarmhf/letsencrypt) | [![](https://images.microbadger.com/badges/image/lsioarmhf/letsencrypt.svg)](https://microbadger.com/images/lsioarmhf/letsencrypt) | [![](https://images.microbadger.com/badges/version/lsioarmhf/letsencrypt.svg)](https://microbadger.com/images/lsioarmhf/letsencrypt)

## Installing ##

```bash
git clone git@github.com:klutchell/docker-motionserver.git ~/motionserver
sudo ~/motionserver/bin/install
~/motionserver/bin/configure
```

## Running ##

```bash
cp ~/motionserver/compose.env.sample ~/motionserver/compose.env
~/motionserver/bin/pull
~/motionserver/bin/up
```

## Contributing ##

n/a

## Author ##

Kyle Harding <kylemharding@gmail.com>

## Credit ##

I give credit where it's due and would like to give a shoutout to the creators of the docker images used in this project:
* [hypriot](https://github.com/hypriot)
* [vividboarder](https://github.com/vividboarder)
* [linuxserver.io](https://www.linuxserver.io/)