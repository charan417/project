# project

VM'S CREATION:1. select required AMI and instance type,networking details,disk size,security groups and launch 2 ubuntu instances.
2.set the hostname permanently using hostnamectl set-hostname "HOSTNAME"
INSTALLATION USING ANSIBLE MODULES:
1.run the linux commands manully and see wheather all the commands are running fine or not
2.after that convert the linux commands into respective ansible modules 
3.write a playbook (project1.yml in my case)
4.inside playbook we write tasks 
5.hosts: ubuntu is  an inventory file which contains ips of all our hostmachines
6. run the playbook file from any machine with the ansible installed using the command ansible-playbook project.yml
7.trouble shoot if any errors exists
