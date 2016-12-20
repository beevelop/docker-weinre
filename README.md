[![Travis](https://shields.beevelop.com/travis/beevelop/docker-weinre.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-weinre)
[![Pulls](https://shields.beevelop.com/docker/pulls/beevelop/weinre.svg?style=flat-square)](https://links.beevelop.com/d-weinre)
[![Layers](https://shields.beevelop.com/docker/image/layers/beevelop/weinre/latest.svg?style=flat-square)](https://links.beevelop.com/d-weinre)
[![Size](https://shields.beevelop.com/docker/image/size/beevelop/weinre/latest.svg?style=flat-square)](https://links.beevelop.com/d-weinre)
[![Release](https://shields.beevelop.com/github/release/beevelop/docker-weinre.svg?style=flat-square)](https://github.com/beevelop/docker-weinre/releases)
![Badges](https://shields.beevelop.com/badge/badges-7-brightgreen.svg?style=flat-square)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# Apache weinre

> weinre (WEb INspector REmote) – pronounced like the word "winery" (or maybe "weiner") – is a debugger for web pages, like FireBug (for FireFox) and Web Inspector (for WebKit-based browsers), except it's designed to work remotely, and in particular, to allow you debug web pages on a mobile device such as a phone.

----

## Run image
```
docker run -d -p 8080:8080 beevelop/weinre
```

Access weinre by hitting http://host-ip:8080 and follow the instructions to enable debugging your applications.

## Use as base image
```Dockerfile
FROM beevelop/weinre:latest
```
