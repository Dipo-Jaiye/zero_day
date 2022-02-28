<h1> Working with Vagrant and Virtual Box </h1>

> To setup Ubuntu VM on local machine  

1. Download Vagrant  
2. Download VirtualBox
3. Run this `vagrant box add ubuntu/focal64`
4. Run this `vagrant init ubuntu/focal64`
5. Run this `vagrant up`
6. Run this `vagrant ssh`
You are now in your Ubuntu VM. To leave, simply do  

1. Run this `logout`
2. Run this `vagrant halt` to shutdown or `vagrant suspend` to put to sleep.

You can always check the current VMs with
* `vagrant status`
