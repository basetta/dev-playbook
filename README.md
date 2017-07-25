# dev-playbook
Mac setup and configuration via Ansible

[![Build Status](https://travis-ci.org/basetta/dev-playbook.svg?branch=master)](https://travis-ci.org/basetta/dev-playbook)

This playbook installs and configures most of the software I use on my Mac for web and software development. 

For more details please have a look at https://github.com/geerlingguy/mac-dev-playbook

## Installation

1. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
  2. [Install Ansible](http://docs.ansible.com/intro_installation.html).
  3. Clone this repository to your local drive.
  4. Run `$ ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
  5. Run `ansible-playbook main.yml -i inventory -K` inside this directory. Enter your account password when prompted.


## Testing the Playbook
[Jeff Geerling](http://www.jeffgeerling.com/) posted instruction on how to build [Mac OS X VirtualBox VM](https://github.com/geerlingguy/mac-osx-virtualbox-vm), on which one can test the playbook.

## Author
[Patrcik Martini](http://basetta.bz), 2017 (originally inspired by [geerlingguy/mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook))