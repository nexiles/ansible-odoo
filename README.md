## Nexiles Odoo (OpenERP) 8 Ansible Playbooks for Debian

Based on: https://github.com/kwanso/ansible-odoo

### Setup dev enviroment

1. add `192.168.33.2 odoo-dev.nexiles.local` to your hosts
2. Run vagrant up

### Requirements

1. ansible 1.6,  vagrant 1.6
2. odoo cloned to `~/develop/nexiles/odoo`:

    $ cd ~/develop/nexiles
    $ git clone git@github.com:nexiles/odoo.git

### Development

Addons go to `../addons`, so clone this directory to your
addons-development dir, and have the addons located there.
