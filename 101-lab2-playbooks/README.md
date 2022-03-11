## Lab 2 - Ansible Playbooks

The files in this repo include exercise-playbook.yaml and hosts.yaml. These two files work in conjuction to complete the assigned tasks. The exercise-playbook.yaml contains all of the individual playbook tasks combined into one file to allow for each task to be run consecutively. The exercise-playbook yaml calls the hosts.yaml file in order to create matches with the two routers listed under the [cisco] grouping. The IP address match allows ansible to connect to the routers in question and apply the playbook. 

Along with the previous 2 files, also contained in this repository are the separate variable files that hold variables specific to each router's configuration. This is found in the inventory folder. 
