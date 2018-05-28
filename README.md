### VAGRANT Provisioning for FLASK App

### Requirements
Please download latest version of applications below considering operating systems. 

- Vagrant / https://www.vagrantup.com/downloads.html
- VirtualBox / https://www.virtualbox.org/wiki/Download_Old_Builds_5_1

### Prologue

- Make sure requirements are done and clone this repository to your environment & `cd` into the project root. 
- `vagrant up` to provision the virtualbox VM

### Steps

1. `vagrant ssh` to go into the virtual machine
2. `cd /vagrant/app`
3. `python FlaskApp.py` to start the development server
4. Point your browser to http://0.0.0.0:4000


Note: For all configuration details,'Vagrantfile'can be checked further. 

