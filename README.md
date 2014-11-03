pouta-ansible-demo
==================

Simple Ansible demo to deploy a machine to Pouta

To use this demo you will need:
 - Ansible 1.8:
   http://docs.ansible.com/intro_installation.html
 - OpenStack command line tools:
   http://docs.openstack.org/user-guide/content/install_clients.html
 - Access to pouta:
   https://research.csc.fi/pouta-access
 - Your Pouta openstack RC file:
   https://research.csc.fi/pouta-install-client

To launch the demo:

    ansible-playbook -i demo.hosts -c local create-instance.yml
    ansible-playbook -i demo.hosts setup-instance.yml
