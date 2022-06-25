# Infrastructure and deployment of Udagram

## Overview

This project is aimed at providing the required infrastructure code along with the necessary supporting software


## Building
You can create infrastructure using the code below

##### Create network infrastructure

`./create.sh udagramNetworkInfra network.yml network-parameters.json`

##### Create servers infrastructure

`./create.sh udagramServerInfra servers.yml server-parameters.json`

##### Updating Infrastructure
To update infrastructure you can use scripts `update.sh` Below is the script to update a server infrastructure
`./update.sh udagramServerInfra servers.yml server-parameters.json` 

## URL to verify the app is running properly,
http://udagr-webap-1wa2zoj2qz86g-453793089.us-east-1.elb.amazonaws.com/