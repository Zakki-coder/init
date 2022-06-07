PC->Switch->Router->Firewall->Modem->Internet(lots of routers)->Inverse ordering on receiving end.

Switch (?vaihde?, L2)
	Switch is used to connect multiple machines.
	Switch is smart HUB is not. Hub sends info for every machine connected trough it. Switch knows which L2(data link layer) MAC address is connected to physical ports. Swithc is layer 2 device. So it doesnt know anything about IP address, which is L3. Switch learns MAC addresses and stores them in CAM(Content Addressable Memory) table. Switch, frame, L2. Frame is like package, but its frame. Acces points of Wifi are stupid like hubs.
ARP(address resolution protocol)
	Switch knows only MAC adresses, so if we only have IP address we are going to need ARP, which is going to ask every member of switch network their IP's by using broadcast address and if match is found, matching MAC address is returned.

Router(gateway, L3)
	Routers are used to connect LAN's to other networks or WAN(Wide area network "the internet") 
