Vagrant
Website: https://www.vagrantup.com/
Source: https://github.com/hashicorp/vagrant

Vagrant is a tool for building and distributing development environments.

Development environments managed by Vagrant can run on local virtualized platforms such as VirtualBox or VMware, in the cloud via AWS or OpenStack, or in containers such as with Docker or raw LXC.

Vagrant provides the framework and configuration format to create and manage complete portable development environments. These development environments can live on your computer or in the cloud, and are portable between Windows, Mac OS X, and Linux.

Quick Start

Package dependencies: Vagrant requires bsdtar to be available on your system PATH to run successfully.

For the quick-start, we'll bring up a development machine on VirtualBox because it is free and works on all major platforms. Vagrant can, however, work with almost any system such as OpenStack, VMware, Docker, etc.

First, make sure your development machine has VirtualBox installed. After this, download and install the appropriate Vagrant package for your OS.

To build your first virtual environment:

vagrant init hashicorp/bionic64
vagrant up
Note: The above vagrant up command will also trigger Vagrant to download the bionic64 box via the specified URL. Vagrant only does this if it detects that the box doesn't already exist on your system.

Getting Started Guide
To learn how to build a fully functional development environment, follow the getting started guide.

Installing from Source

System Requirements
x64 Windows 7/8/8.1/10;

VirtualBox 6.0.0 and later versions.
https://www.virtualbox.org/


Administrative privilege is required.# ansible2019
