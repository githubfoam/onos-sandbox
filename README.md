# onos-sandbox
onos testing on ubuntu minimalCD

-vagrant up  
-vagrant ssh  
-ansible --version  
-ansible-playbook /vagrant/deploy.yml  
-vagrant destroy   

Accessing the CLI and GUI  
https://wiki.onosproject.org/display/ONOS/Accessing+the+CLI+and+GUI

ONOS is the only SDN controller platform that supports the transition from legacy “brown field” networks to SDN “green field” networks
https://onosproject.org/

Software-defined networking (SDN) technology is a novel approach to cloud computing that facilitates network management and enables programmatically efficient network configuration in order to improve network performance and monitoring
https://en.wikipedia.org/wiki/Software-defined_networking

Installation/MinimalCD
The minimal iso image will download packages from online archives at installation time instead of providing them on the install media itself. Downloading packages at install time reduces the size of the iso image to approximately ~40MB depending on architecture  
https://help.ubuntu.com/community/Installation/MinimalCD

App deployment, configuration management and orchestration - all from one system.  
https://www.ansible.com

HashiCorp Vagrant provides the same, easy workflow regardless of your role as a developer, operator, or designer. It leverages a declarative configuration file which describes all your software requirements, packages, operating system configuration, users, and more.  
https://www.vagrantup.com

VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use
https://www.virtualbox.org
