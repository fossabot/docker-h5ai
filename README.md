# h5ai-base

[h5ai project](https://larsjung.de/h5ai/)

[![Layers](https://images.microbadger.com/badges/image/pad92/docker-h5ai.svg)](https://microbadger.com/images/pad92/docker-h5ai) [![GitHub issues](https://img.shields.io/github/issues/pad92/docker-docker-h5ai.svg)](https://github.com/pad92/docker-docker-h5ai) [![Docker Automated build](https://img.shields.io/docker/automated/pad92/docker-h5ai.svg?maxAge=2592000)](https://hub.docker.com/r/pad92/docker-h5ai/) [![Docker Build Status](https://img.shields.io/docker/build/pad92/docker-h5ai.svg?maxAge=2592000)](https://hub.docker.com/r/pad92/docker-h5ai/) [![Docker Pulls](https://img.shields.io/docker/pulls/pad92/docker-h5ai.svg)](https://hub.docker.com/r/pad92/docker-h5ai/)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fpad92%2Fdocker-h5ai.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fpad92%2Fdocker-h5ai?ref=badge_shield)

# Usage

## Commun

```
docker container run -it -p 80:80 \
  -v $PWD/sharing-file:/share \
  pad92/docker-h5ai
```

## With custom h5ai options

For overide [options.json](https://raw.githubusercontent.com/lrsjng/h5ai/v0.29.0/src/_h5ai/private/conf/options.json) file is into `/usr/share/h5ai/_h5ai/private/conf/options.json`

```
docker container run -it -p 80:80 \
  -v $PWD/sharing-file:/share \
  -v $PWD/options.json:/usr/share/h5ai/_h5ai/private/conf/options.json \
  pad92/docker-h5ai
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fpad92%2Fdocker-h5ai.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fpad92%2Fdocker-h5ai?ref=badge_large)