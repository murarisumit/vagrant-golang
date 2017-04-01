# -*- mode: ruby -*-
# # vi: set ft=ruby :
#
# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provision :shell do |shell|
    shell.path = "bin/golang.sh"
    shell.privileged = true
  end

  config.vm.box_check_update = false
  config.vm.provider "virtualbox" do |vb|
    vb.customize ["modifyvm", :id, "--accelerate3d", "off"]
    vb.customize [ "guestproperty", "set", :id, "/VirtualBox/GuestAdd/VBoxService/--timesync-set-threshold", 10000 ]
    vb.memory = 4096 
    vb.cpus = 2
  end
end
