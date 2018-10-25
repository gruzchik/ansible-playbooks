Variants of start execution playbook

with installed ssh key:
-------------------------

ansible-playbook -i inventory playbook.yml

without installed ssh key:
--------------------------

ansible-playbook -i inventory playbook.yml -k -c paramiko -v
