# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  config.vm.box = "miniubuntu"
  #Install python for ansible. In case ubuntu 16.04 minimalCD ISO required for remote deployments
   config.vm.provision "shell", inline: <<-SHELL
   test -e /usr/bin/python || (apt -qqy update && apt install -qqy python-minimal)
   SHELL
   config.vm.provision "shell", inline: <<-SHELL
	   sudo apt-get install software-properties-common -y
	   sudo apt-add-repository ppa:ansible/ansible -y
	   sudo apt-get update -y
	   sudo apt-get install ansible -y
   SHELL
end
