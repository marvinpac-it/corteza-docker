# Deployment of Corteza using docker-compose on Vagrant #

This repository contains a Vagrantfile that will setup an ubuntu focal box and install docker and docker-compose in it.

The /vagrant folder contains the docker-compose.yml file.

### How do I get set up? ###

* Install VirtualBox
* Install Vagrant
* Clone this repository and cd into it

```bash
vagrant up
vagrant ssh
cd /vagrant
docker-compose up -d
```
