# Integration Platform

A integration platfrom framework using Java + Redhat Fuse + Docker and more


Download and Install Docker

-Docker installation includes: Docker-compose, Docker-machine

-- From: https://store.docker.com/editions/community/docker-ce-desktop-mac
-- Version: Docker version 18.03.1-ce
-- Doc: https://docs.docker.com/docker-for-mac/

-Test: docker run hello-world

<!--  1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal. -->

-Test2: Build a server:  docker run -d -p 80:80 --name webserver nginx
--This step host a nginx server inside docker container, nginx can be swtch to other application servers, using docker to share the host OS, and harness the entire hardware collection

$ docker container ls
$ docker container stop webserver
$ docker container ls -a
$ docker container rm webserver
$ docker image ls
$ docker image rm nginx

image is the component that container may grab and run

-Run Command Doc: https://docs.docker.com/engine/reference/commandline/run/



RedHat Jboss Fuse