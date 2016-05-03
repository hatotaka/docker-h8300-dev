docker-h8300-dev 
===============

This image is h8300 cross-compilation environment.

Available on [Docker Hub](https://hub.docker.com/r/hatotaka/h8300-dev/).

## Download

```
$ docker pull hatotaka/h8300-dev
```

## Make

```
$ docker run -v $(pwd):/src --rm hatotaka/h8300-dev make -C /src
```
