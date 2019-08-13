# [plinecom/docker-centos-blender-2.8-builder-v1](https://hub.docker.com/r/plinecom/docker-centos-blender-2.8-builder-v1/)

## Usage

### Automatic build

    docker run plinecom/docker-centos-blender-2.8-builder-v1

### Automatic build (advanced)

    docker create --name blender-builder plinecom/docker-centos-blender-2.8-builder-v1

Repeat:

    docker start blender-builder
    docker logs --follow blender-builder

### Manual build

    docker run -it plinecom/docker-centos-blender-2.8-builder-v1 bash

Use devtoolset-7.

    scl enable devtoolset-7 bash

Run /usr/bin/start or go to $HOME/blender-git/.

## Source

[github.com/plinecom/docker-centos-blender-2.8-builder-v1](https://github.com/plinecom/docker-centos-blender-2.8-builder-v1)
