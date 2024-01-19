# Barbatus
roteus@cygnus:~$ ip addr show
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host 
       valid_lft forever preferred_lft forever
2: enp42s0: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc fq_codel state DOWN group default qlen 1000
    link/ether 04:7c:16:73:25:1b brd ff:ff:ff:ff:ff:ff
3: wlo1: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc noqueue state UP group default qlen 1000
    link/ether bc:f4:d4:0d:e8:23 brd ff:ff:ff:ff:ff:ff
    altname wlp41s0
    inet 192.168.0.109/24 brd 192.168.0.255 scope global dynamic noprefixroute wlo1
       valid_lft 5481sec preferred_lft 5481sec
    inet6 fe80::f6c5:167f:a414:93cb/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
proteus@cygnus:~$ 
