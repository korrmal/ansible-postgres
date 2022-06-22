# ansible-postgres
Ansible role for postgresql cluster with patroni

Must be add jinja2_extensions = jinja2.ext.do to ansible.cfg

You need to set cluster_name and vip_address for keepalived

Usage

ansible-playbook -i hosts playbook.yml -e "cluster_name=psql vip_address=192.168.0.10"
