drop
===
Docker images that you can use to execute a program with less
privileges

Currently, this repository offers these images:

* alpine:3.6 (Dockerfile.alpine)
* debian:stable (Dockerfile.debian)

## Build
To build the image, you select a Dockerfile first (<dockerfile>).
Then you build it using the following command: ```docker build -f <dockerfile> -t drop:<debian/alpine> .```