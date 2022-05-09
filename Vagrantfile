# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define :alpha do |alpha|
    alpha.vm.box = "gusztavvargadr/docker-linux"
    alpha.vm.network "private_network", ip: "192.168.56.101"
    alpha.vm.hostname = "alpha"
  end

  config.vm.define :beta do |beta|
    beta.vm.box = "gusztavvargadr/docker-linux"
    beta.vm.network "private_network", ip: "192.168.56.102"
    beta.vm.hostname = "beta"
  end

  config.vm.define :gamma do |gamma|
      gamma.vm.box = "gusztavvargadr/docker-linux"
      gamma.vm.network "private_network", ip: "192.168.56.103"
      gamma.vm.hostname = "gamma"
    end
end
