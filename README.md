# Setup

sudo apt-install ansible
git clone https://github.com/stetak/rpi
cd rpi
ansible-playbook -i inventories/boostrap.inv --ask-vault-pass bootstrap.yml
