# -*- mode: ruby -*-
Vagrant.configure("2") do |config|
  config.vm.box = "primestrategy/kusanagi"
 
  # config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.provider "virtualbox" do |vb|
    vb.customize ["modifyvm", :id, "--memory", "1024"]
  end
end
