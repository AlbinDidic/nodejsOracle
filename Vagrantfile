Vagrant.configure(2) do |config|
  config.vm.box = "Albin/nodejsOracle"
  config.vm.network "forwarded_port", guest: 9000, host: 9000
  config.vm.network "forwarded_port", guest: 8080, host: 8080
  config.vm.network "forwarded_port", guest: 5858, host: 5858
  #config.vm.network :private_network, ip: "192.168.56.123"
  config.vm.synced_folder './code/', '/home/vagrant/code'
end