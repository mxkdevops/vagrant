# vagrant
17/09/2023 05:27 am 
vagrant-vmware-virtualbox-automation
### Install vagrant 
```
https://developer.hashicorp.com/vagrant/downloads
```

### Install vagrant through community edition through chokoloty
```
https://community.chocolatey.org/packages/vagrant
choco install vagrant
```

### Install Vagrant VMware Utility
```
https://developer.hashicorp.com/vagrant/downloads/vmware
```
### centos 7 vagrant box
```
https://app.vagrantup.com/centos/boxes/7
```
### Edit vagrant file 
```
open with notepad

```
### List of vagrant command
```
vagrant box list
vagrant init centos/7
vagrant init centos/8
vagrant init geerlingguy/ubuntu1604
vagrant init ubuntu/jammy64
vagrant up
vagrant ssh
vagrant status
vagrant global-status
vagrant global-status --prune
vagrant halt
vagrant suspend
vagrant reload
vagrant up
ls ~/.vagrant.d/
```
### Vagrant Networking 
uncomment this from 
notepad :  Vagrantfile
config.vm.network "private_network", ip: "192.168.56.14"
config.vm.network "public_network"
### Provisioning
### RAM, CPU , etc
config.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
  #   vb.gui = true
  #
  #   # Customize the amount of memory on the VM:
     vb.memory = "1600"
   end
### Multivm
### Documentation 
