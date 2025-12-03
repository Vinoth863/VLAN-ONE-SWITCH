# VLAN-ONE-SWITCH
A single switch was configured with multiple VLANs to segment the LAN network (192.168.0.0/24) into separate departments. VLAN2, VLAN3, VLAN4, and VLAN5 were assigned to the IT, Finance, Marketing, and HR departments, respectively, to ensure network isolation and proper traffic management.

# SWITCH CLI-COMMANDS
Switch (config# int fa 0/1

Switch(config-if)# switchport mode access

Switch(config-if)# switchport access van 2

Switch (config# int fa 0/2

Switch(config-if)# switchport mode access

Switch(config-if)# switchport access van 2

Switch (config# int fa 0/3

Switch(config-if)# switchport mode access

Switch(config-if)# switchport access van 2



(ABOVE COMMANDS All separate department vlan commands same)
