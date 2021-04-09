# dhcp-discovery

## Example Usage

```
$ sudo python3 dhcp-discovery.py eth0
* waiting for DHCPOFFER
* constructing DHCPDISCOVER packet
* sending DHCPDISCOVER...
* DHCPOFFER received:
ip offered = 192.168.1.28
message-type = 2
server_id = 192.168.1.1
lease_time = 86400
renewal_time = 43200
rebinding_time = 75600
subnet_mask = 255.255.255.0
broadcast_address = 192.168.1.255
router = 192.168.1.1
domain = b'lan'
name_server = 192.168.1.1
* done
``
