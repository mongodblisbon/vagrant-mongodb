<h2>Vagrant and Puppet configuration for MongoDB</h2>

Vagrant configuration with puppet to create a Virtual Box machine with 
Ubuntu Server 14.04 & MongoDB



**installation:**

* Install Vagrant
* Install Virtual
* Clone the repository git clone [git://github.com/mongodblisbon/vagrant-mongodb.git](git://github.com/mongodblisbon/vagrant-mongodb.git)


**running:**

* Run - vagrant up<br>
* SSH - vagrant ssh<br>
* Halt - vagrant halt<br>


**to access mongo from your machine:**

* mongo localhost 27017

*attention: you may have this port occupied by your installation for mongodb in your machine*


**development:**

by default this vagrantfile have this configuration for shared folder between the host and the VM
*[config.vm.synced_folder "~/Projects", "/vagrant"](https://github.com/mongodblisbon/vagrant-mongodb/blob/master/Vagrantfile#L23)*


**Puppet Manifest will install:**

* MongoDB - 2.6.\*
* wget
* git
* vim 
* htop
* g++
