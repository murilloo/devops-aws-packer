# devops-aws-packer-pipeline
Example pipeline using Packer to create an AMI in AWS with customized configuration

## Requirements
- Packer >= 1.5.1
- Python version = 3.7.5
- Ansible = 2.9.2

## Goals
- To bootstrap a server image running Amazon Linux 2 (ami-062f7200baf2fa504)
- To install Nginx on top of it
- To publish it to Amazon as a new AMI

## Running
```
$ packer validate template.json
$ packer build template.json
```
