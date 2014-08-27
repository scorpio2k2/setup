setup
=====

Deployment Scripts for CentOS 6


## Installation

Execute the following commands at your servers command-line:

	$ yum -y install git
	$ git clone https://github.com/darcyliu/setup.git
	$ cd setup
	$ sh {script_file}.sh
	
###PPTP

	$ curl -OL https://raw.github.com/darcyliu/setup/master/centos_pptp.sh
	$ sh centos_pptp.sh

###LAMP(Apache)

	$ curl -OL https://raw.github.com/darcyliu/setup/master/centos_lamp.sh
	$ sh centos_lamp.sh
	
###LEMP(nginx)
	$ curl -OL https://raw.github.com/darcyliu/setup/master/centos_lemp.sh
	$ sh centos_lemp.sh
	
##Recommand Cloud Service
* [Google Compute Engine](https://cloud.google.com/products/compute-engine/) 
* [Linode](http://www.linode.com/?r=8dd6ddd391fc320d9f55ad101e051bde767df599)
* [DigitalOcean](https://www.digitalocean.com/?refcode=e655c19f2abb)


