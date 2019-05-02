# alpine-dev

#### [alpine-x64-dev](https://hub.docker.com/r/forumi0721alpinex64/alpine-x64-dev/)
[![](https://images.microbadger.com/badges/version/forumi0721alpinex64/alpine-x64-dev.svg)](https://microbadger.com/images/forumi0721alpinex64/alpine-x64-dev "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/forumi0721alpinex64/alpine-x64-dev.svg)](https://microbadger.com/images/forumi0721alpinex64/alpine-x64-dev "Get your own image badge on microbadger.com") [![Docker Stars](https://img.shields.io/docker/stars/forumi0721alpinex64/alpine-x64-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721alpinex64/alpine-x64-dev/) [![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721alpinex64/alpine-x64-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721alpinex64/alpine-x64-dev/)
#### [alpine-aarch64-dev](https://hub.docker.com/r/forumi0721alpineaarch64/alpine-aarch64-dev/)
[![](https://images.microbadger.com/badges/version/forumi0721alpineaarch64/alpine-aarch64-dev.svg)](https://microbadger.com/images/forumi0721alpineaarch64/alpine-aarch64-dev "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/forumi0721alpineaarch64/alpine-aarch64-dev.svg)](https://microbadger.com/images/forumi0721alpineaarch64/alpine-aarch64-dev "Get your own image badge on microbadger.com") [![Docker Stars](https://img.shields.io/docker/stars/forumi0721alpineaarch64/alpine-aarch64-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721alpineaarch64/alpine-aarch64-dev/) [![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721alpineaarch64/alpine-aarch64-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721alpineaarch64/alpine-aarch64-dev/)
#### [alpine-armhf-dev](https://hub.docker.com/r/forumi0721alpinearmhf/alpine-armhf-dev/)
[![](https://images.microbadger.com/badges/version/forumi0721alpinearmhf/alpine-armhf-dev.svg)](https://microbadger.com/images/forumi0721alpinearmhf/alpine-armhf-dev "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/forumi0721alpinearmhf/alpine-armhf-dev.svg)](https://microbadger.com/images/forumi0721alpinearmhf/alpine-armhf-dev "Get your own image badge on microbadger.com") [![Docker Stars](https://img.shields.io/docker/stars/forumi0721alpinearmhf/alpine-armhf-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721alpinearmhf/alpine-armhf-dev/) [![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721alpinearmhf/alpine-armhf-dev.svg?style=flat-square)](https://hub.docker.com/r/forumi0721alpinearmhf/alpine-armhf-dev/)



----------------------------------------
#### Description

* Distribution : [Alpine Linux](https://alpinelinux.org/)
* Architecture : x64
* Appplication : -
    - Development environment
* Base Image
    - [forumi0721/alpine-x64-base](https://hub.docker.com/r/forumi0721/alpine-x64-base/)
    - [forumi0721/alpine-aarch64-base](https://hub.docker.com/r/forumi0721/alpine-aarch64-base/)
    - [forumi0721/alpine-armhf-base](https://hub.docker.com/r/forumi0721/alpine-armhf-base/)



----------------------------------------
#### Run

* x64
```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721alpinex64/alpine-x64-dev:latest
```

* aarch64
```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721alpineaarch64/alpine-aarch64-dev:latest
```

* armhf
```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721alpinearmhf/alpine-armhf-dev:latest
```



----------------------------------------
#### Usage

* Run docker container and login.
    - Default user name : forumi0721



----------------------------------------
#### Docker Options

| Option             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Ports

| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Volumes

| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables

| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| RUN_USER_NAME      | login user name (default:forumi0721)             |
| RUN_USER_UID       | login user uid (default:1000)                    |
| RUN_USER_GID       | login user gid (default:100)                     |



----------------------------------------
* [forumi0721alpinex64/alpine-x64-dev](https://hub.docker.com/r/forumi0721alpinex64/alpine-x64-dev/)
* [forumi0721alpinearmhf/alpine-armhf-dev](https://hub.docker.com/r/forumi0721alpinearmhf/alpine-armhf-dev/)
* [forumi0721alpineaarch64/alpine-aarch64-dev](https://hub.docker.com/r/forumi0721alpineaarch64/alpine-aarch64-dev/)

