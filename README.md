# coursework

1. sudo apt-get install openvswitch-switch
2. sudo systemctl stop NetworkManager
3. sudo ovs-vsctl add-br ovs_sw1
4. sudo ovs-vsctl add-port ovs_sw1 enx7cc2c642b186
5. sudo ifconfig enx7cc2c642b186 0
6. sudo vim /etc/network/interfaces
7. sudo ifup enx7cc2c642b186 or sudo ifconfig enx7cc2c642b186 up
8. add nameserver 8.8.8.8 to /etc/resolv.conf 
