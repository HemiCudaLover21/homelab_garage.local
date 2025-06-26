# my homelab garage.local
Information about my networking homelab with useful notes detailed technology information
<H3>Archetecture</H3>
<img src="https://github.com/HemiCudaLover21/homelab_garage.local/blob/main/HOMELAB1.0.png">
<H4>systems</H4>
<H4>TODO</H4>
Switch Authentication through radius server with AD
Install Samba on toolbooth.garage.local for second DC for HA and redundancy
use ansible to automatically wr net cisco switches
<H4>tollbooth.garage.local</H4>
<img src="https://github.com/HemiCudaLover21/homelab_garage.local/blob/main/Screenshot_20250626_172550.png">
TFTP for switch configs
<H4>gamma2.garage.local</H4>
<img src="https://github.com/HemiCudaLover21/homelab_garage.local/blob/main/Screenshot_20250626_172458.png">
Authoritative DNS for network
Authoritative DHCP for network
Primary Domain Controller
<H4>networking</H4>
OSPF IPV4 network
<H4>TODO</H4>
HA engineering with HSRP or VRRP to backup transam node
IPV6 migration maybe?
contanerized HA montioring
<h4>TRANSAM</h4>
default gateway for all PROXMOX nodes
<h4>Tornado</h4>
internet access for all nodes reaching the internet
PAT overload enabled
