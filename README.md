cp -r inventories/* /etc/ansible/

cp -r roles/* /etc/ansible/roles 

ansible-playbook site.yml -e "HOST=name.name" -e "ROLE=hosts" -e "dpc_name=Youname"