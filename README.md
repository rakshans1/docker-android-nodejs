[![Travis](https://img.shields.io/travis/rakshans1/docker-android-nodejs.svg)](https://travis-ci.org/rakshans1/docker-android-nodejs)
[![Pulls](https://img.shields.io/docker/pulls/rakshans1/android-nodejs.svg)]()
[![Layers](https://img.shields.io/imagelayers/layers/rakshans1/android-nodejs/latest.svg)]()
[![Size](https://img.shields.io/imagelayers/image-size/rakshans1/android-nodejs/latest.svg)]()


![rakshans1/android-nodejs](/icon.png?raw=true)
# Latest Android with Node.js v8 and npm
### based on [Android 8 (1.8.0_111)](https://github.com/rakshans1/docker-android)
----
### Pull from Docker Hub
```
docker pull rakshans1/android-nodejs:latest
```

### Build from GitHub
```
docker build -t rakshans1/android-nodejs github.com/rakshans1/docker-android-nodejs
```

### Run image
```
docker run -it rakshans1/android-nodejs bash
```

### Use as base image
```Dockerfile
FROM rakshans1/android-nodejs:latest
```