## Ansible Configuration

__How to create ansible configuration?__

>__Step 1:__ Create a directory.

`mkdir <name of directory>`

`cd <name of directory>`

>__Step 2:__ Create you own ansible.cfg file.

>>`vi ansible.cfg`

Insert
```Linux Alpine
[defaults]

inventory = ./inventory

remote_user = <server name of the other device>`
```

_By default you can check the content of ansible.cfg file_  `etc/ansible/ansibel.cfg`

## Ansible Inventory
__How to create ansible inventory?__

__Step 1:__ Create an inventory file.

`vi inventory`

Insert

`[device name]`

`IP Address of remote_user`

or simply put the IP address

`IP Address of remote_user` 

## Ansible Ad-hoc Commands

__How to create ad-hoc ansible command with setup and shell module?__



For more information visit the following:

   [Ansible Configuration](https://tip.instructure.com/courses/14414/pages/2-dot-2-ansible-configuration?module_item_id=810770)

   [Ansible Inventory](https://docs.ansible.com/ansible/latest/user_guide/basic_concepts.html)

   [Ad-hoc Commands](https://docs.ansible.com/ansible/latest/user_guide/intro_adhoc.html)
