# docker-cheat-sheet
Another Docker Cheat Sheet

* [Why](#why)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [QuickStart](#quickstart)
* [Containers](#containers)
* [Images](#images)
* [Misc](#misc)
* [Todo](#todo)
* [Links](#links)

## Why

A quick/pretty basic Docker cheat sheet. Other ones (see [Links](#links)) are insteresting but I wanted to start my own.

## Prerequisites

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

### Useful commands

````
some docker code
````

## Images

More infos about managing docker images 

## Misc

Misc infos. Keep away the usual mess.

## Todo

More stuff needs to be added here ! :-)

## Links

* [wsarget - Docker cheat sheet](https://github.com/wsargent/docker-cheat-sheet)
