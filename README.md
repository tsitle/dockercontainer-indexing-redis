# Redis data structure server Docker Container for AARCH64, ARMv7l, X86 and X64

## Docker Container usage
To start a Redis 5.0 container execute

```
$ ./dc-run.sh 5.0

```

To stop the container use

```
$ ./dc-stop.sh 5.0

```

You may replace the version number with any number that corresponds  
to an available Docker Image (indexing-redis-\<ARCH\>:\<VERSION\>).

## Required Docker Image
The Docker Image **indexing-redis-\<ARCH\>** will automaticly be downloaded from the Docker Hub.  
The source for the image can be found here [https://github.com/tsitle/dockerimage-indexing-redis](https://github.com/tsitle/dockerimage-indexing-redis).
