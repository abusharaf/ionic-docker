![Type Lightweight](https://img.shields.io/badge/Type-Lightweight-35a4de.svg) 
[![Build Status](https://travis-ci.org/abusharaf/ionic-docker.svg?branch=master)](https://travis-ci.org/abusharaf/ionic-docker)
[![HitCount](http://hits.dwyl.io/abusharaf/ionic-docker.svg)](http://hits.dwyl.io/abusharaf/ionic-docker) 
[![Beta On_Going_Changes](https://img.shields.io/badge/Beta-On_Going_Changes-brightgreen.svg)](https://badge.fury.io/gh/abusharaf%2Fionic-docker) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
[![GitHub version](https://badge.fury.io/gh/abusharaf%2Fionic-docker.svg)](https://badge.fury.io/gh/abusharaf%2Fionic-docker)

# ionic-docker 

<p align="center"> 
  <a href="https://www.ionic.io" target="_blank">
    <img src="https://raw.githubusercontent.com/abusharaf/ionic-docker/master/icons/rsz_ionic-logo.png">
  </a>
</p>

  [![npm version](https://badge.fury.io/js/ionic.svg)](https://beta.ionicframework.com/docs) 
  [![Cordova 8.0.0](https://img.shields.io/badge/Cordova-8.0.0-orange.svg)](https://www.npmjs.com/package/cordova)


> A ready made docker image that runs ionic framework with Cordova, Capacitor, and Stencil JS frameworks embedded in the container _,based on lightweight linux alpine image,_ to ease the development of hyrbid mobile & PWA, this image will be the base for further improvments.


## Description [![Base Alpine](https://img.shields.io/badge/Base-Alpine-red.svg)](https://hub.docker.com/_/alpine/)

The aim of this image is to have a neat, clean, and small in size development environment for ionic framework - along with Cordova, capacitor, and stencil JS - for developing and testing ionic based applications without the need to install the framework on the machine itself, and also have the ability to test new beta versions without affecting the stable one if it's installed on the local machine.

## Usage

### Pull image from docker hub

```
docker pull abusharaf/ionic:latest
```

### Build image from Github Dockerfile
```
docker image build -t abusharaf/ionic github.com/abusharaf/ionic-docker
```

### Run docker image
```
docker container run -it -p 8100:8100 abusharaf/ionic /bin/sh
```

### Use as base image
```dockerfile
FROM abusharaf/ionic:latest
```

___
