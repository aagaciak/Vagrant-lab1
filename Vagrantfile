Vagrant.configure("2") do |config|

  config.vm.provider "virtualbox" do |v|
    v.check_guest_additions = true
	v.gui = true
	v.memory = 2048
	v.cpus = 2
  end

  config.vm.box_download_insecure=true
  config.vm.box = "hashicorp/bionic64"
  config.vm.network "private_network", ip: "192.168.50.4"
  
end

