# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|
 
  config.vm.box = "centos-6.5"

 config.vm.define :one do |one| 
    one.vm.hostname = "one.cluster"
    one.vm.network :private_network, ip: "192.168.0.101"
    one.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", 1024]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
end

config.vm.define :two do |two| 
    two.vm.hostname = "two.cluster"
    two.vm.network :private_network, ip: "192.168.0.102"
    two.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", 1024]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
end
config.vm.define :three do |three| 
    three.vm.hostname = "three.cluster"
    three.vm.network :private_network, ip: "192.168.0.103"
    three.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", 1024]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
end

config.vm.define :four do |four| 
    four.vm.hostname = "four.cluster"
    four.vm.network :private_network, ip: "192.168.0.104"
    four.vm.provider :virtualbox do |vb|
      vb.customize ["modifyvm", :id, "--memory", 1024]
      vb.customize ["modifyvm", :id, "--cpus", "1"]
    end
end

end
