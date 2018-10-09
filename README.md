# opencpn-docker

Dockerfile for [openCPN](https://opencpn.org/).

## Build
``` bash
$ docker build -t opencpn .
```

## Run
```bash
$ docker run -it --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix -v /charts/folder/path:/home/developer opencpn
```

## Charts
Download charts into charts folder.

## Thanks
[Fábio Rehm](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)