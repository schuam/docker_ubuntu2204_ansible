# Ubuntu 22.04 Docker Image for Ansible Role Testing

I use the Dockerfile contained in this repository to build a docker image that
I can use to test Ansible roles on an Ubuntu 22.04 system. It's based on the
official [Ubuntu docker image](https://hub.docker.com/_/ubuntu) and
just installs some additionally needed packages.

So far id does not support systemd, but I might add that in the future.

You can find the
[image on dockerhub](https://hub.docker.com/repository/docker/schuam/docker_ubuntu2204_ansible).

