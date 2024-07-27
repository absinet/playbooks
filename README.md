# playbooks
Ansible Playbooks
Just a collection of playbooks for testing on CentOS and Solaris

to run syntax check:
ansible-playbook -i ./hosts ansible_copy.yml --syntax-check

to run (ansible target host file in same directory as playbook)
ansible-playbook -i ./hosts ansible_copy.yml
