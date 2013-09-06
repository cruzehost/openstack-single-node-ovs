openstack-single-node-ovs
=========================

Openstack single node test installation with OVS (OpenVswitch)

1. Install git on the machine
 apt-get update -y 
 apt-get install git -y

2. Clone the repo
 git clone https://github.com/cruzehost/openstack-single-node-ovs.git

3. Execute the script to set up openstack
 cd openstack-single-node-ovs/
 python stack.py
 
 The default password for Horizon and Mysql is "secret". 
