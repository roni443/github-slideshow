# Network basics 

**Networks types**
1. LAN - local area network, the smalles network. 
all the devices can talk with each other without enthernet. 

2. WAN - wide area network, the way to connect outside the local network.

3. MAN - metropolitan area network, cities that have connection to the city (Tel-Aviv).
most of the time, will be open network. 

4. SAN - storage area network, servers network, provides efficient transfer of unusually large data sizes.

**Network Device** 
1. End Devices - the device that conect in the end of the comunication. (Telephons, PC, Frigerator)

2. Media - from the word "Medium" - in between.
transferring data: Plastic fiber, Radio frequncies. 

3. Intermediary Devices - devices that managing the network. (Switch, Router)

**NIC**
Network Interface Controller, allow an eb=nd device to send and receive information.
Other name: 
- Network Adapter
- LAN Adapter
- Physical Network Interface 

**Intermediary Devices**
Act as bridges, to understend what the bast way to connects the networks I want and need. 

Switch - for multiple end devices to communicate with each other. 
Switch using MAC addresses to pass information from one end devices to other.

1. HUB - fool switch, working on MAC adress only, getting information from the router and get the information ti the end device, send the information to every device on the network - not secure. 

2. Layer 2 Switch - know to identify between end devices with MAC adress. 

3. Later 3 Switch - know everything like layer 2 but can also function as a router.
share IP adresses and MAC adresses, make briges, splits informetion to spesific end device (not like HUB).

**Brodcast & Collision Domains**
Collision Domains happens when every one can hear each other like in HUB. 
When alot of devices toking in the same time its cousing burden on the network and un orderly information. 

In Layer 2 Switch it getting the information only to the device that ask for it. it more secure and not cousing burden on the network. 

ARP - we will use Brodcast by ARP when the Router dont know who send the request for the information. Then it will send the information to all the devices until he getting answer that its the device that need the information.

**Other Devices**
- Access Point - let devices to connect to him for comunication.
he will get the information to the Router ot the server. 

- Firewall - answering a Yes or No question. 
today ther have a lot of feature that get in the Firewall like the Router. 

- WLC - Wireless LAN Controller, allows us to connect a lot of wireless Access Points like Mesh.

- Home Router - takes all the features like: Assign an IP, Infotmation Routing, Ports, Network connection. can work like: Access Points, Firewall, Switch. 

**Network Media & Cables**
1. CAT5e Cable - Cable ethernet.
limits the cable lenght. 

2. UTP - Unshielded Twisted-Pair, common copper cable.
STP - Shielded Twiste-Pair, have additional protection. 

3. Fiber Media - transfering the information on light in glass cables. 

**Network Topology**
- Point To Point - one cable from on point to other.
- Star - when we have a main device that connect evrything to him, like Router or Switch. 
- Mesh - all the devices communicate with each other in the network,
- Hybrid - have at least two ways of connection Topology.

**3-Tier Architecture** 
Help us to understand and build our network. 
from the main device to the end device. 

**Network Classes**
Subnet masks define which addressws in an octet can be used in an IP address. 
- C class - only the part can change ( 225.225.255.**000**)
- B class - only the 2 last parts can change (225.225.**000.000**)
- A class - only the first part stay the same (225.**000.000.000**)

**Protocols**
Language that help all the device to comunicate with eacch other. 
- IP - Idetification protocol. 
- DNS - Dynamic Name Service, used to translate domain name to IP (Web pages). 
- DHCP - Dynamic Host Configuration, protocol that distribute IP to devices. 
- http - Hypertext Transfer Protocol, used to transfer text and picture mostly web pages.
- https - like HTTP but secure and encrypts.

**Comeands**
- Ping - its the most common commend in administrative networking activity. (Ping X.X.X.X)
- IP Confige - displays a CP IP configuration. (IP Confige)
- Nsloockup - CP use IP addresses to conmunicate with each other, this commen help us find the IP address or the web address. (nsloocup 8.8.8.8 or nslookup cyber.com)
- Tracert - displays all thr station along the way. (Tracert X.X.X.X or Tracert 8.8.8.8)

**Wiereless Networks**
Information is transmitted on radio frequencies.
The big problems is that its not secure.
In WIFI we have passwords and encryption.

