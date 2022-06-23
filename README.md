# Infrastructure and deployment of Udagram

## Overview

This project is aimed at providing the required infrastructure code along with the necessary supporting software


## Building
Create infrastructure using the code below

### Create network infrastructure

`./create.sh udagramInfra network.yml network-parameters.json`

### Create servers

`./create.sh udagramServer servers.yml server-parameters.json`

## Updating Infrastructure
To update infrastructure you can use scripts `update.sh`
by running `./update.sh udagramServer servers.yml server-parameters.json` for servers, or `./update.sh udagramInfra network.yml network-parameters.json` for network infrastructure.

## Deleting Infrastructure
To delete infrastructure you can use scripts `delete-network.sh` and `delete-server.sh`.