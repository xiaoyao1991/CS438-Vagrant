# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define :alpha do |alpha|
    alpha.vm.box = "ubuntu/trusty64"
    alpha.vm.provision :shell, path: "bootstrap.sh"
    alpha.vm.network :private_network, ip: "10.0.0.10"
    alpha.vm.hostname = "alpha"
  end

  config.vm.define :beta do |beta|
    beta.vm.box = "ubuntu/trusty64"
    beta.vm.provision :shell, path: "bootstrap.sh"
    beta.vm.network :private_network, ip: "10.0.0.11"
    beta.vm.hostname = "beta"
  end
end
