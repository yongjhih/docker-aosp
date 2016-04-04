## Usage
```sh
$ curl -L https://github.com/yongjhih/docker-aosp/raw/master/docker-aosp > ~/bin/docker-aosp
$ chmod a+x ~/bin/docker-aosp

$ docker-aosp bash -c '. build/envsetup.sh && cd vendor/google/ && mm'
```
