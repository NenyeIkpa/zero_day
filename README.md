# How to set up a virtual environment in your PC(MacOsx)
Tools used for this project are: VirtualBox and Vagrant

## VirtualBox
This is a virtual machine(VM).
https://www.virtualbox.org/wiki/Downloads

## Vagrant
Vagrant is a command line utility for managing the life cycle of VMs.
https://developer.hashicorp.com/vagrant/downloads

### Step 1
Download and install VirtualBox and Vagrant on your PC using the links provided above.

### Step 2
Open the Terminal and execute the following commands:

#### Add the Ubuntu 20.04(Focal)image to your box list ####
`% vagrant box add ubuntu/focal64`

#### Create your first virtual machine ####
`% vagrant init ubuntu/focal64`
(This will generatea vagrant file with base "ubuntu/focal64". You only need to execute this command once to create your new virtual machine.)

#### Start your virtual machine ####
`% vagrant up`

#### Get inside your virtual machine ####
`% vagrant ssh`

### To leave the virtual enviroment(VE)
`% exit`
(This command terminates the session and exits the VE)
