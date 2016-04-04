[![Docker Tag](https://img.shields.io/github/tag/yongjhih/docker-aosp.svg)](https://hub.docker.com/r/yongjhih/aosp/tags/)
[![Docker Pulls](https://img.shields.io/docker/pulls/yongjhih/aosp.svg)](https://hub.docker.com/r/yongjhih/aosp/)
[![Docker Stars](https://img.shields.io/docker/stars/yongjhih/aosp.svg)](https://hub.docker.com/r/yongjhih/aosp/)
[![Docker Size](https://img.shields.io/imagelayers/image-size/yongjhih/aosp/latest.svg)](https://imagelayers.io/?images=yongjhih/aosp:latest)
[![Docker Layers](https://img.shields.io/imagelayers/layers/yongjhih/aosp/latest.svg)](https://imagelayers.io/?images=yongjhih/aosp:latest)
[![Gitter Chat](https://img.shields.io/gitter/room/yongjhih/docker-aosp.svg)](https://gitter.im/yongjhih/docker-aosp)

## Usage
```sh
$ curl -L https://github.com/yongjhih/docker-aosp/raw/master/docker-aosp > ~/bin/docker-aosp
$ chmod a+x ~/bin/docker-aosp

$ docker-aosp bash -c '. build/envsetup.sh && cd vendor/google/ && mm'
```
