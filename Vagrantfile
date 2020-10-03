Vagrant.configure("2") do |config|   
config.vm.define "master" do |subconfig|
    subconfig.vm.box = "centos/7"
    subconfig.vm.hostname = "master"
    subconfig.vm.network :private_network, ip: "10.0.0.10"
    end
config.vm.define "slave1" do |subconfig|
    subconfig.vm.box = "centos/7"
    subconfig.vm.hostname = "slave1"
    subconfig.vm.network :private_network, ip: "10.0.0.11"
    end
config.vm.define "slave2" do |subconfig|
    subconfig.vm.box = "centos/7"
    subconfig.vm.hostname = "slave2"
    subconfig.vm.network :private_network, ip: "10.0.0.12"
    end
config.vm.define "slave3" do |subconfig|
    subconfig.vm.box = "centos/7"
    subconfig.vm.hostname = "slave3"
    subconfig.vm.network :private_network, ip: "10.0.0.13"
    end
config.vm.define "slave4" do |subconfig|
    subconfig.vm.box = "centos/7"
    subconfig.vm.hostname = "slave4"
    subconfig.vm.network :private_network, ip: "10.0.0.14"
    end
end
