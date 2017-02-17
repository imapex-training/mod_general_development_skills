
* The basic Vagrantfile is nearly all just comments and sample configuraitons for customization.  Only a very small part is actually active.  That part is listed here to highlight how little is needed to get started with vagrant
	
	```
	Vagrant.configure(2) do |config|
	  config.vm.box = "centos/7"
	end		
	```
	
