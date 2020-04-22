# Node Cookbook

Description:


## List of what to install
- NodeJs
- Nginx
- pm2 and npm


## Commands

## Test Locally

1. Running my Unit Test:
````
chef exec rspec
````

2. Running my Intergration Test and closing the machine:
````
kitchen test
````

## Test in AWS

Running Intergration Test in AWS:
````
KITCHEN_YAML=kitchen_cloud.yml kitchen test
````
