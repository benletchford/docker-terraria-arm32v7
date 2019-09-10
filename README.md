# docker-terraria-arm32v7
Terraria in Docker for the Raspberry Pi 

This is based off of https://github.com/ryansheehan/terraria and changed to use the `arm32v7/mono` base image.

## Building
```
$ docker build -t terraria-arm32v7 .
```

## Running and generating a world

Please [ryansheehan's](https://github.com/ryansheehan/terraria) documentation, it will be equivalent except use the image you just built (`terraria-arm32v7`).
