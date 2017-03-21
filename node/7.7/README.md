# Node

A Windows Server Core Docker container image with Node.js 7.7.3 installed.

## Building

```
docker build -t node .
docker tag node:latest node:7.7.3
```

## Onbuild

```
docker build -t node:onbuild onbuild
```