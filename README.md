drop
===
Docker images that you can use to execute a program with less
privileges

Currently, this repository offers these images:

* alpine:3.6 (Dockerfile.alpine)
* debian:stable (Dockerfile.debian)

## Build
To build the image, you select a Dockerfile first (\<dockerfile\>).
Then you build it using the following command:

```docker build -f <dockerfile> -t drop:<debian/alpine> .```

## Environment Variables
- ```USERID```: The ID of the user (Defaults to ```9001```)
- ```GROUPID```: The ID of the user's group (Defaults to ```9001```)
- ```CUSER```: The name of the user (Defaults to ```cuser```)
- ```UMASK```: The umask to be set (Defaults to ```077```)
