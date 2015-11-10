# S2I HTTPD Sample

Just a quick sample of how to build a docker image using
[Source-to-Image](https://github.com/openshift/source-to-image).

This image simply installs and runs httpd. It can be built with Fedora, CentOS,
and RHEL.

## Building the image

### Prerequisites

1. [Source-to-Image](https://github.com/openshift/source-to-image)

2. Git

### Instructions

To build, run:

```.shell
s2i build git@github.com:ajsmith/s2i-httpd-sample.git docker.io/centos
```
