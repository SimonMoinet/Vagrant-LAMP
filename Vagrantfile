Vagrant.configure(2) do |config|

	# Selection de la box
	config.vm.box = "debian/jessie64"

	config.vm.provision "chef_solo" do |chef|

		chef.cookbooks_path = "cookbooks"

		chef.add_recipe "apache2"
	end

end