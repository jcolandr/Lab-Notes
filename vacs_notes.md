#VACS Notes

###IP Addresses

	192.168.10.190 - vacs-pnsc  
	192.168.10.191 - vacs-vsum  
	192.168.10.192 - vacs-vsm  
	192.168.10.193 - vacs-esx0-mgmt-vmkernel  
	192.168.10.194 - vacs-esx0 n1k-vmkernel  
	192.168.10.195 - vacs-esx0 n1k-vtep  
	192.168.10.196 - vacs-esx1-mgmt-vmkernel  
	192.168.10.197 - vacs-esx1 n1k-vmkernel  
	192.168.10.198 - vacs-esx1 n1k-vtep  

###UCSD Notes

vacs-subnet pool
  
	192.168.0.0 /16  
	64 subnets  
	
vacs-vxlan-pool

	14000-14100
	
vacs-static-ip-pool

	192.168.10.160-192.168.10.189

uplink port-profile

	name: vacs-n1kv-uplink
	vlan 401
	native vlan 1
	physical interface: yes
	
