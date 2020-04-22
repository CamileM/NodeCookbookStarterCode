# Node Cookbook 'node'

DESCRIPTION:

## What is Chef?

- Chef is an Configuration Management Tool, chef allows files on the machine to configure
the recipes, and it ensures that machine is responding accordingly.

## How to use Cookbook?



## List of what to install
- NodeJs
- Nginx
- pm2 and npm


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
