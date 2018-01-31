[![Circle CI](https://circleci.com/gh/codeworksio/docker-openjdk8.svg?style=shield "CircleCI")](https://circleci.com/gh/codeworksio/docker-openjdk8)&nbsp;[![Size](https://images.microbadger.com/badges/image/codeworksio/openjdk8.svg)](http://microbadger.com/images/codeworksio/openjdk8)&nbsp;[![Version](https://images.microbadger.com/badges/version/codeworksio/openjdk8.svg)](http://microbadger.com/images/codeworksio/openjdk8)&nbsp;[![Commit](https://images.microbadger.com/badges/commit/codeworksio/openjdk8.svg)](http://microbadger.com/images/codeworksio/openjdk8)&nbsp;[![Docker Hub](https://img.shields.io/docker/pulls/codeworksio/openjdk8.svg)](https://hub.docker.com/r/codeworksio/openjdk8/)

Docker OpenJDK 8
================

Customised OpenJDK 8 base image.

Installation
------------

Builds of the image are available on [Docker Hub](https://hub.docker.com/r/codeworksio/openjdk8/).

    docker pull codeworksio/openjdk8

Alternatively you can build the image yourself.

    docker build --tag codeworksio/openjdk8 \
        github.com/codeworksio/docker-openjdk8

Testing
-------

    make build start log
