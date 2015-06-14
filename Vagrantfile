Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "nosql"

  #config.vm.network "forwarded_port", guest: 5432, host: 5432       # PostgreSQL
  #config.vm.network "forwarded_port", guest: 8443, host: 8443       # Tomcat (yoosers)

  config.vm.provider "virtualbox" do |vb|
    vb.name = "nosql"
    vb.memory = "1024"
  end

  # Previament cal haver instal·lat el plugin 'vagrant-cachier' amb:
  #     vagrant plugin install vagrant-cachier
  if Vagrant.has_plugin?("vagrant-cachier")
    config.cache.scope = :box
  end

  config.vm.provision :shell, path: "provision/install-mongo.sh"
  #config.vm.provision :shell, path: "provision/install-puppet-modules.sh"
  #config.vm.provision "puppet"
end
