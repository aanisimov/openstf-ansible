# openstf-ansible
Deployment ansible playbook for openstf

Deploy instructions:
1. Set your host in `inventory`
2. Set values for variables in `roles/vars/main.yml`
3. Run `ansible-playbook -i inventory openstf.yml`
