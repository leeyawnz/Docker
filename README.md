# Docker Documentation
This is my own personal documentation of the common Docker commands
As most OS are Linux in DevOps, this in the context of Linux


## Setting up Docker
    $ sudo apt-get remove docker docker-engine docker.io containerd runc
<br>
    $ sudo apt-get update
<br>
    $ sudo apt-get install \
      ca-certificates \
      curl \
      gnupg \
      lsb-release

    $ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg

## Checking Docker Version
    $ docker --version
