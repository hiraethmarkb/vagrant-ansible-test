# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  # Every Vagrant virtual environment requires a box to build off of.
  config.vm.box = "CentOS 6.4 x86_64 Minimal"

  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  config.vm.network :private_network, ip: "192.168.33.10"

  # Example for VirtualBox:
  #
  config.vm.provider :virtualbox do |vb|
     # Use VBoxManage to customize the VM. For example to change memory:
     vb.customize ["modifyvm", :id, "--memory", "1024"]
  end
end
