# Vagrant-Ansible
* One controller node and 4 slave nodes.
* Master node ansible pre-installed. 
* Clone the repo and ```vagrant up``` will complete the setup
* To confirm nodes are running use ```vagrant global-status``` inside the directory 
* Use ```vagrant ssh master``` to get into the master node
* IP's are preconfigured on the Vagrant file. 
* Master node is configured with 10.0.0.10 and subsequent ip's reserved for slave's 
