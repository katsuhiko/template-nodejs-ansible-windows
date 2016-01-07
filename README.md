# Template for Nodejs App Developmettem by Ansible

## Requirements

* [VirtualBox](https://www.virtualbox.org)
* [Vagrant](http://vagrantup.com)
* Git
  * [Git for windows](https://git-for-windows.github.io/)

## How To Build The Virtual Machine

Vagrant:

    host $ vagrant plugin install vagrant-vbguest

Building the virtual machine:

    host $ git clone https://github.com/katsuhiko/template-nodejs-ansible-windows.git
    host $ cd template-nodejs-ansible-windows
    host $ vagrant up
