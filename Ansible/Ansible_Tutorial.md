# Ansible Tutorial

Ansible is a radically simple IT automation tool that automates cloud provisioning configuration management, application deployment and many other IT needs.

Ansible is an agentless tool which requires only one admin host to have it installed and controlling all the other nodes.

Ansible uses an “agentless” model where changes are pushed out to machines on demand. This is different than Puppet and Chef, where there
is a central server that is seen as the single source of truth, and machines periodically check with the server to ensure that they have the latest copy of everything they need.
This has its advantages and disadvantages: the good news is that once you make changes, you can instantly push these changes out to machines without waiting for a daemon
to check if there are any changes. The bad news is that you are responsible for getting updates out to your machines, whereas with Puppet and Chef you can just commit your changes and know that they’ll be rolled out soon.

# Install Ansible in amazon Aws linux 
sudo amazon-linux-extras install ansible2

# Install using python
pip install ansible



