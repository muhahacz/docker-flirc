# docker-flirc
Based on Ubuntu 17.10

It seems that Flirc has problems with musl (eventually glibc) in Alpine.

`docker rm -f flirc; docker run -it --device=/dev/bus/usb/001/003  --name flirc muhahacz/docker-flirc flirc_util version`

