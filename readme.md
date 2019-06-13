# Shadowsocks-libev Dockerfile
This Dockerfile build an image for [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev/) with [v2ray-plugin](https://github.com/shadowsocks/v2ray-plugin), based on Alpine Linux.

Current version:
- shadowsocks-libev: v3.3.0
- v2ray-plugin: v1.1.0


## Quick Start

Get the docker image by running the following commands:

```bash
docker pull nickleefly/shadowsocks-libev
```

Start a instance:

```bash
docker run -d --name=shadowsocks-libev -p 8388:8388/tcp -p 8388:8388/udp --restart=always nickleefly/shadowsocks-libev
```
