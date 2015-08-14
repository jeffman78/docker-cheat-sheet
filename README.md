# docker-cheat-sheet
Another Docker Cheat Sheet

* [Why](#why)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [QuickStart](#quickstart)
* [Containers](#containers)
* [Images](#images)
* [Dockerfile](#dockerfile)
* [Misc](#misc)
* [Todo](#todo)
* [Links](#links)

## Why

A quick/pretty basic Docker cheat sheet. Other ones (see [Links](#links)) are insteresting but I wanted to start my own.

##Prerequisites

None (at least for the time being). This section will be expanded as time goes on. 

## Installation

For the time being, I assume you have Docker installed and running. On my side, I'm currently playing with Scaleway.

## QuickStart

Start a container with an interactive shell
```
docker run --rm -i -t ubuntu /bin/bash
```

** ````--rm```` : the container will be silently discarded when disconnecting

## Containers

### Lifecyle

* [`docker create`](https://docs.docker.com/reference/commandline/create) creates a container but does not start it.
* [`docker run`](https://docs.docker.com/reference/commandline/run) creates and starts a container in one operation.
* [`docker stop`](https://docs.docker.com/reference/commandline/stop) stops it.
* [`docker start`](https://docs.docker.com/reference/commandline/start) will start it again.
* [`docker restart`](https://docs.docker.com/reference/commandline/restart) restarts a container.
* [`docker rm`](https://docs.docker.com/reference/commandline/rm) deletes a container.
* [`docker kill`](https://docs.docker.com/reference/commandline/kill) sends a SIGKILL to a container.
* [`docker attach`](https://docs.docker.com/reference/commandline/attach) will connect to a running container.
* [`docker wait`](https://docs.docker.com/reference/commandline/wait) blocks until container stops.

### Others commands

* [`docker ps -a`](https://docs.docker.com/reference/commandline/ps) show ALL containers. Omitting the `-a` option only show running containers.
* [`docker exec -it container /bin/bash`] (https://docs.docker.com/reference/commandline/exec) enters to a running container using a bash shell.
*

````
some docker code
````

## Images

The "registry" is a place where local images are stored.

* [`docker images`](https://docs.docker.com/reference/commandline/images) lists images available in the local registry
* [`docker rmi `](https://docs.docker.com/reference/commandline/rmi) remove a specific image from the local registry
More infos about managing docker images 

## Dockerfile

### Dockerfile syntax


### Using Dockerfile
* [`docker build -t username/imagename .`](https://docs.docker.com/reference/commandline/build) build a new image based on the Dockerfile located in the current directory. The created image will be named "username/imagename".


## Misc

Misc infos. Keep away the usual mess.

## Todo

More stuff needs to be added here ! :-)

## Links & Credits

### Credits

* This Docker cheat sheet is inspirated from [wsarget - Docker cheat sheet](https://github.com/wsargent/docker-cheat-sheet)

### Links

* Nothing (at least for yet)
