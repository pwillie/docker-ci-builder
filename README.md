# docker-ci-builder

This image has build tools and scripts for running builds in a Docker container.

## Tags
* arm32v7-debian
        
     includes the `amd64` qemu-arm-static binary to allow building arm binaries on an amd64 host.  It does however rely on `binfmt` support from the host kernel.
