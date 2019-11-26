# Ansible

ansible-playbook --step playbook.yml -> Execute your yml step by step

ansible-playbook -C playbook.yml -> Execute your yml with dry run and check your yml validation

ansible-playbook -v playbook.yml -> Verbose logs ( you can increase log level with vv, vvv, vvvv)

ansible-playbook playbook.yml -K -> Become password(for users which you set for become user)
