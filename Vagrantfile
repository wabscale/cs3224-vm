# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.provider "virtualbox" do |vb|
    vb.name = "xv6_box"
    vb.memory = 1024
    vb.cpus = "2"
  end
  config.vm.provision "shell", path: "provision.sh"
end
