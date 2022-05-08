# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define :alpha do |alpha|
    alpha.vm.box = "gusztavvargadr/docker-linux"
    alpha.vm.network "private_network", ip: "10.0.0.10"
    alpha.vm.hostname = "alpha"
  end

  config.vm.define :beta do |beta|
    beta.vm.box = "gusztavvargadr/docker-linux"
    beta.vm.network "private_network", ip: "10.0.0.11"
    beta.vm.hostname = "beta"
  end

  config.vm.define :gamma do |gamma|
      gamma.vm.box = "gusztavvargadr/docker-linux"
      gamma.vm.network "private_network", ip: "10.0.0.12"
      gamma.vm.hostname = "gamma"
    end
end
