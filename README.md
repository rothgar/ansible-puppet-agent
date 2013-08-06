Puppet
=====

This Ansible playbook will deploy puppet agent to all of your clients specified in /etc/ansible/hosts.

It first copies the puppetlabs repo and then the EPEL repo to address any dependancies.

This has been tested on RedHat but should also work with CentOS with small modifications.