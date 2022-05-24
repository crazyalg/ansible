Playbook work on Debian 10

1)install ansible and requirements
pip install -r requirements.txt

2)Create file hosts. Example hosts_example

3)Run playbook for preparation os
Example:
ansible-playbook setup_wireguard.yml -l vpn01 -D

4)Run playbook for install wireguard
Example:
ansible-playbook setup_wireguard.yml -l vpn01 -D