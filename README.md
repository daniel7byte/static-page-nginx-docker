# This is my first container with Docker
## Instructions
Run this:
To create the image
``` bash
$ docker build -t daniel7bytetest
```
To create the container with the last image
``` bash
$ docker run -p 3000:80 -d --name daniel7byteapp daniel7bytetest
```