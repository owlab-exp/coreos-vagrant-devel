# CoreOS Vagrant Test Environment

## Requirements
* Prepare a private docker registry serving all the docker images in fleet files.
* Set host name of a docker-registry: the name is currently "obzen-reg"

## Before vagrant up
1. Copy user-data.pre to user-data
2. Edit the user-data to meet your environment

## Services in fleet directory
1. zookeeper@.service: Zookeeper 3.4.7 
2. kafka@.service: Kafka 2.11-0.9.2.2
