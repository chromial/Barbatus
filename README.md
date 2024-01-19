# Barbatus

sudo arp -d 192.168.0.110  # From the target host
route -n  # Check the routing table
ping 192.168.0.110  # Check connectivity to the client

proteus@cygnus:~$ sudo arp -d 192.168.0.110  # From the target host
[sudo] password for proteus: 
proteus@cygnus:~$ route -n  # Check the routing table
Kernel IP routing table
Destination     Gateway         Genmask         Flags Metric Ref    Use Iface
0.0.0.0         192.168.0.1     0.0.0.0         UG    600    0        0 wlo1
169.254.0.0     0.0.0.0         255.255.0.0     U     1000   0        0 wlo1
192.168.0.0     0.0.0.0         255.255.255.0   U     600    0        0 wlo1
proteus@cygnus:~$ ping 192.168.0.110  # Check connectivity to the client
PING 192.168.0.110 (192.168.0.110) 56(84) bytes of data.
^C
--- 192.168.0.110 ping statistics ---
12 packets transmitted, 0 received, 100% packet loss, time 11243ms




sudo arp -d 192.168.0.109  # From the client
ping 172.29.64.1
sudo iptables -L
