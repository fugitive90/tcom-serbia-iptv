# tcom-serbia-iptv
Configuration files for setting IPTV and PPPoe on Linux/Unix machines for Telekom Serbia VDSL

# Requirements

 * Linux/Unix OS
 * Two external NIC or 2x USB to ETH adapter
 * Modem DSL
 * Support for VLAN
 * Tcpdump/Wireshark

# Setup 
```
                        eth0      eth2
DSL line ----- Modem ----- OurRouter  ----- Wifi router
                               \eth2
                                \
                                STB
```
# Legend:

eth0 - Wan interface that goes to the DSL modem

eth1 - LAN iface where STB is connected to

eth2 - LAN iface which is connected to a WiFi modem


