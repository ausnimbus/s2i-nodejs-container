# NodeJS (SCL) S2I Docker images

[![Build Status](https://travis-ci.org/ausnimbus/s2i-nodejs-scl.svg?branch=master)](https://travis-ci.org/ausnimbus/s2i-nodejs-scl)

This repository contains the source for building various versions of
the Node.JS application as a reproducible Docker image
[source-to-image](https://github.com/openshift/source-to-image)
to be run on [AusNimbus](https://www.ausnimbus.com.au/).

Images are built with NodeJS RPM packages from SCL.
The resulting image can be run using [Docker](http://docker.io).

## Versions

The versions currently supported are:

- 0.10 (deprecated)
- 4
