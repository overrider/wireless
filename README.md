wireless
========

Very simple OpenBSD console wireless connection manager.

Store your usually used network configs inside a simple config file
and save yourself typing by connecting to your wlan by issuing 
./wireless network-name inside your console. Wireless will issue
the right ifconfig commands to setup your connection and then get
an IP address via DHCP.

Installation:
cp wireless /usr/local/bin/
cp wireless.cfg /etc/

Useage:
# lists all wireless networks configured inside your config
wireless

# connects to network-name as long as it was found inside your config
# and is in range
wireless network-name 	
