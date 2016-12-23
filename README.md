# joshtronic
An ansible script to run tests on Cloud Provider instances based on the IMHO excellent framework provided by @Joshtronic in his article https://joshtronic.com/2016/12/18/8gb-showdown-linode-digitalocean-lightsail-vultr/ 

## Background
In order to run the script the following are requirements
- An Ubuntu 14.04 instance at a Cloud Provider ( ideally an instance with 8GB RAM comparable to what Jost uses for his tests)
- Ansible version 2.1
- The SSH key

## To Run The Scripts
You can do something like this from the commandline
- ansible-playbook playbook.yml -i 'ABC.XXX.YYY.ZZZ,' --private-key=~/Documents/key.pem

## Improvements or comments
Please comment in the issues on improvements. Am not sure yet what is the best way to submit results. But would be useful to the community if someone uses these scripts to publish the results.
