# Node Cookbook 'node'

DESCRIPTION:

- This repo will include the details on using the Nodejs. This cookbook is set
to install Nodejs, Nginx, PM2 and NPM from its source.
## What is Chef?

- Chef is an Configuration Management Tool, chef allows files on the machine to be
configured, and it ensures that the machine is responding correctly and accordingly.

## How to use Cookbook?

- In a small and detailed concept, in order to run the recipe file we will need to
provision the code on to the machine as it will allow us to test the environment.

## Pre-requisites (Things We've Used):
- Chef
- GitHub
- NodeJs
- Nginx
- PM2
- NPM
- AWS CLI Version 2


## Installs:
- NodeJs
- Nginx
- PM2
- NPM

## Commands

### Test Locally

1. Running my Unit Test:
````
chef exec rspec
````

2. Running my Integration Test and closing the machine:
````
kitchen test
````

### Test in AWS

Running Integration Test in AWS:
````
KITCHEN_YAML=kitchen_cloud.yml kitchen test
````
