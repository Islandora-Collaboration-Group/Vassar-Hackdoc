# Documentation: Help with Vagrant

## Table of Contents

* Glossary
* Important: Recommended Order of Installation
* Install Vagrant on PC or Mac
* How to Run Vagrant (Vagrant Up)
* Vagrant Command-Line Interface
* Vagrant Plugins
* More Great Help Documentation

## [* Glossary](https://www.vagrantup.com/docs/)

* **vagrant** - Vagrant is a tool for building complete development environments. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases development/production parity, and makes the "works on my machine" excuse a relic of the past. Vagrant provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team. To achieve its magic, Vagrant stands on the shoulders of giants. Machines are provisioned on top of VirtualBox, VMware, Docker Containers, AWS, or any other provider. Then, industry-standard provisioning tools such as Ansible, Chef, Puppet, or shell scripts can be used to automatically install and configure software on the machine.

* * *


## Important: Recommended Order of Installation

1. Install git

2. Install virtualbox

3. Install vagrant

4. Install ansible

* * *


## Install Vagrant on PC or Mac

1. Download and install: [https://www.vagrantup.com/downloads.html](https://www.vagrantup.com/downloads.html) 

**Stay updated by installing the newest release**

* * *


## How to Run Vagrant (Vagrant Up)

1. Download and install VirtualBox: https://www.virtualbox.org/wiki/Downloads

2. Download and install Vagrant: http://www.vagrantup.com/downloads.html

3. Download the desired VM vagrant.box file (if a zip file, then unzip it into a subdirectory on your laptop)

4. Using a Command Line Interface, navigate to the VM directory from step 3 and run the command: vagrant up

5. Note that this step will take a while as the VM downloads and installs a full virtual environment

6. Test the VM by opening your web browser and navigating to: http://localhost:8080/name_of_directory

**Stay updated by installing the newest release**

* * *


## Vagrant Command-Line Interface

Always remember to be in the folder where the Vagrantfile is located to run Vagrant commands!

* vagrant list-commands	lists all available vagrant commands

* vagrant box			(add,list,remove,update) manages Vagrant boxes (VMs)

* vagrant up     		creates and configures guest machines

* vagrant ssh			ssh into a running Vagrant machine and gives access to a shell

* vagrant halt			shuts down the running machine Vagrant is managing.

* vagrant destroy		stops the running machine & destroys all resources 

* vagrant reload --provision  	halt followed by an up but runs any configured provisioners

* vagrant global-status		Displays a cached state of all active Vagrant environments

See complete listing: [Vagrant Command-Line Interface](https://www.vagrantup.com/docs/cli/)

* * *


## Vagrant Plugins

* https://github.com/mitchellh/vagrant/wiki/Available-Vagrant-Plugins

* Snapshots (for Vbox snapshot backups) 

    * vagrant plugin install vagrant-vbox-snapshot

    * https://github.com/dergachev/vagrant-vbox-snapshot

* Vagrant-bindfs (NFS - for performance and sharing)

    * vagrant plugin install vagrant-bindfs

    * https://github.com/gael-ian/vagrant-bindfs

* Vagrant-hosts-updater (no more editing /etc/hosts files)

    * vagrant plugin install vagrant-hostsupdater

    * https://github.com/cogitatio/vagrant-hostsupdater

* Vagrant-vbguest (for correct VB Guest Additions on guests)

    * vagrant plugin install vagrant-vbguest

    * https://github.com/dotless-de/vagrant-vbguest

* * *


## More Great Help Documentation

1. [Vagrant Getting Started](https://www.vagrantup.com/docs/getting-started/)

2. [Atlas (For Vagrant boxes)](https://atlas.hashicorp.com/)

3. [How to make Vagrant performance not suck](https://stefanwrobel.com/how-to-make-vagrant-performance-not-suck)

4. [Slow connection?](https://github.com/mitchellh/vagrant/issues/1807)

5. [Additional Resources](http://chromaticsites.com/blog/vagrant-overview-tips-and-resources)

