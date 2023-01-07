### Project Title - Deploy a high-availability web app using CloudFormation

This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:

#### network.yml

This script contains the code to set up the network infrastructure for the web application.

#### network-parameters.json

This is the network.yml parameter file

#### role.yml

This script contains the code to set up the IAM role that gives the servers yhe permission to download files from an s3 bucket

#### role-parameter.json

The parameter file or role.yml

#### server.yml

This file contains the code to set up the server infrastructure, it also gives the servers IAM role and sets up a bastion host to connect to our servers.

#### server-parameter.yml

The parameter file for the server.yml
