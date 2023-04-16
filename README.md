# iaac-wordpress

Automated Wordpress setup using Vagrant provisioning.

How to use it:
- clone this repository
- cd into /iaac-wordpress/
- type: vagrant up
- search for the ip address using 'grep "private_network"' and copy address 
    (you may want to change the ip in that line: 'config.vm.network "private_network", ip: "192.168.56.19"'
- copy the address and open it in your browser
