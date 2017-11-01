Vagrant.configure("2") do |config|
  config.vm.define "master" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-16.04"
	subconfig.vm.network "private_network", ip: "90.90.90.10"
	subconfig.vm.hostname = "master"
  end

  config.vm.define "node1" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-16.04"
	subconfig.vm.network "private_network", ip: "90.90.90.11"
	subconfig.vm.hostname = "node1"
  end

  config.vm.define "node2" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-16.04"
	subconfig.vm.network "private_network", ip: "90.90.90.12"
	subconfig.vm.hostname = "node2"
  end
  
  config.vm.define "node3" do |subconfig|
    subconfig.vm.box = "bento/ubuntu-16.04"
	subconfig.vm.network "private_network", ip: "90.90.90.13"
	subconfig.vm.hostname = "node3"
  end
end