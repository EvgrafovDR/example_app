# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.define "study" do |study|
  end
  config.vm.provider "virtualbox" do |v|
    v.memory = 2048
  end
  config.vm.box = "ubuntu/focal64"
  config.vm.network "private_network", ip: "192.168.255.212"
  config.vm.provider :virtualbox do |vb|
      vb.name = "study"
  end
end
