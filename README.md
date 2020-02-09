# ansible.aci
This ansible code is to serve the purpose of deploying ACI resources.  

Inventory file is hosted in group_vars. 

Main.yml is importing plays per folder.

ansible-playbook -i hosts.ini main.yml to run from main or from each dir simply call the name of the playbook.

