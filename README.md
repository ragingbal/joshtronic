# joshtronic
An ansible script to run tests on Cloud Provider instances based on the IMHO excellent framework provided by @Joshtronic in his article .

## Background
In order to run the script the following are requirements
- An Ubuntu 14.04 instance at a cloud provider
- Ansible version 2.1
- The SSH key

## To Run The Scripts
You can do something like this from the commandline
- ansible-playbook playbook.yml -i 'ABC.XXX.YYY.ZZZ,' --private-key=~/Documents/key.pem


##
