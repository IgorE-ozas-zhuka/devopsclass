Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  
  config.vm.network "private_network", ip: "10.0.2.16"
  config.vm.network "public_network"
  
  config.vm.provider "virtualbox" do |vb|
     vb.name = "ubuntu_docker_dz2"
     vb.memory = "1024"
     vb.cpus = 2
   end
   
end