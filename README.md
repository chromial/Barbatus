# Barbatus

ip addr show wlo1

ip route show default

route -n

arp -n

traceroute 192.168.0.110

mtr 192.168.0.110

#on target

ip addr show wlo1; ip route show default; route -n; arp -n; traceroute 192.168.0.110; mtr 192.168.0.110;
--------------------------------

wlo1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default qlen 1000
    link/ether bc:f4:d4:0d:e8:23 brd ff:ff:ff:ff:ff:ff
    altname wlp41s0
    inet 192.168.0.109/24 brd 192.168.0.255 scope global dynamic noprefixroute wlo1
       valid_lft 5077sec preferred_lft 5077sec
    inet6 fe80::f6c5:167f:a414:93cb/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
default via 192.168.0.1 dev wlo1 proto dhcp metric 600 
Kernel IP routing table
Destination     Gateway         Genmask         Flags Metric Ref    Use Iface
0.0.0.0         192.168.0.1     0.0.0.0         UG    600    0        0 wlo1
169.254.0.0     0.0.0.0         255.255.0.0     U     1000   0        0 wlo1
192.168.0.0     0.0.0.0         255.255.255.0   U     600    0        0 wlo1
Address                  HWtype  HWaddress           Flags Mask            Iface
192.168.0.105            ether   38:b1:db:3b:4a:6f   C                     wlo1
192.168.0.1              ether   84:16:f9:25:6c:3f   C                     wlo1
192.168.0.110            ether   fc:34:97:a7:bd:3a   C                     wlo1
traceroute to 192.168.0.110 (192.168.0.110), 30 hops max, 60 byte packets
 1  * * *
 2  * * *
 3  * * *
 4  * * *
 5  * * *
 6  * * *
 7  * * *
 8  * * *
 9  * * *
10  * * *
11  * * *
12  * * *
13  * * *
14  * * *
15  * * *
16  * * *
17  * * *
18  * * *
19  * * *
20  * * *
21  * * *
22  * * *
23  * * *
24  * * *
25  * * *
26  * * *
27  * * *
28  * * *
29  * * *
30 ***
