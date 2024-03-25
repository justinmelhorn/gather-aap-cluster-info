# How to use:
* Fill out inventory with apropriate hosts and variables required
* Fill out credentials.yaml
* Encrypt - ansible-vault encrypt credentials.yaml

## ansible-playbook -i inventory.ini main.yaml -e @credentials.yaml --ask-vault-pass
