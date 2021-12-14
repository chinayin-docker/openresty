Openresty Image
=================

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/chinayin-docker/openresty/Docker%20Image%20CI)
![Docker Image Version (latest semver)](https://img.shields.io/docker/v/chinayin/openresty?sort=semver)
![Docker Image Size (latest semver)](https://img.shields.io/docker/image-size/chinayin/openresty?sort=semver)
![Docker Pulls](https://img.shields.io/docker/pulls/chinayin/openresty)

OpenResty is a full-fledged web application server by bundling the standard nginx core, lots of 3rd-party nginx modules, as well as most of their external dependencies.

### Supported tags and respective `Dockerfile` links

![](https://img.shields.io/docker/v/chinayin/openresty/1.19)

### Image Variants

- `openresty:<version>`

### Usage

You can use the image directly, e.g.

```
docker run --rm -it chinayin/openresty:1.19
```

The images are built daily and have the security release enabled, so will contain any security updates released more
than 24 hours ago.

You can also use the images as a base for your own Dockerfile:

```
FROM chinayin/openresty:1.19
```
