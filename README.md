(Inital set of files - not yet working. Uses default Vagrant's default insecure SSH key)

A set of Ansible playbooks, for provisioning a development LAMP stack on a Cent OS based VM, through Vagrant.

It is based upon an example set of playbooks, available at https://github.com/ansible/ansible-examples/tree/master/lamp_simple, (c) 2013 AnsibleWorks, Inc.

And includes some of my own additions for setting up a dev environment.

This LAMP stack can be on a single node or multiple nodes. The inventory file 'hosts' defines the nodes in which the stacks should be configured.

The stack can be deployed using the following command:

    ansible-playbook -i hosts site.yml
