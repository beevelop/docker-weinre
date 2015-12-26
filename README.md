[![Travis](https://img.shields.io/travis/beevelop/docker-weinre.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-weinre)
[![Docker Pulls](https://img.shields.io/docker/pulls/beevelop/weinre.svg?style=flat-square)](https://links.beevelop.com/d-weinre)
[![ImageLayer](https://badge.imagelayers.io/beevelop/weinre:latest.svg)](https://imagelayers.io/?images=beevelop/weinre:latest)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# Apache weinre

> weinre (WEb INspector REmote) – pronounced like the word "winery" (or maybe "weiner") – is a debugger for web pages, like FireBug (for FireFox) and Web Inspector (for WebKit-based browsers), except it's designed to work remotely, and in particular, to allow you debug web pages on a mobile device such as a phone.

----
### Pull from Docker Hub
```
docker pull beevelop/weinre:latest
```

### Build from GitHub
```
docker build -t beevelop/weinre github.com/beevelop/docker-weinre
```

### Run image
```
docker run -it -p 8080:8080 beevelop/weinre bash
```

Access weinre by hitting http://host-ip:8080 and follow the instructions to enable debugging your applications.

### Use as base image
```Dockerfile
FROM beevelop/weinre:latest
```