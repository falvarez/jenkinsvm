Vagrant.configure("2") do |config|
  config.vm.box = "robertwe/centos7-with-jenkins"
  config.vm.network "private_network", ip: "192.168.33.80"
  config.vm.synced_folder ".", "/vagrant"
  config.ssh.insert_key = false
  config.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.name = "Jenkins"
  end
end
