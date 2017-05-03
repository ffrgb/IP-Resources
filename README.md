# IP-Resources

* FFRGB IPv4: 10.90.0.0/16
* FFRGB IPv6: fdef:1337::/32

## Partition 1 (Regensburg Stadt)
### V4: 10.90.0.0/19
* 10.90.0.1  : Link-Local IP des Knotens
* 10.90.0.11 : gw01
* 10.90.0.14 : gw04
* 10.90.1.10 : Timo
* 10.90.1.11 : Trantor
* 10.90.1.12 : KHG Pi
* 10.90.1.21 : EgeRouter (Neupfarr)
* 10.90.1.22 : EgeRouter (Zeis)
* 10.90.1.25 : Aruba AP (Neupfarr)
* 10.90.1.26 : Aruba AP (TBD)
* 10.90.1.27 : Aruba AP (Gloria)
* 10.90.1.28 : Aruba AP (Kehlheim)
* 10.90.2.0-10.90.9.254: DHCP Range gw01
* 10.90.10.1-10.90.18.254 DHCP Range gw04

### V6: fdef:1337:f00f:cafe::/64
* fdef:1337:f00f:cafe::1  : Link-Local IP des Knotens
* fdef:1337:f00f:cafe::11 : gw01
* fdef:1337:f00f:cafe::14 : gw04
* fdef:1337:f00f:cafe::1:11/64 Trantor

## Partition 2 (Umland)
### V4: 10.90.32.0/19
### V6: fdef:1337:f10f:cafe::/64

## Partition 3
### V4: 10.90.64.0/19
### V6: fdef:1337:f20f:cafe::/64

## Partition 4
### V4: 10.90.96.0/19
### V6: fdef:1337:f30f:cafe::/64

## Partition 5
### V4: 10.90.128.0/19
### V6: fdef:1337:f40f:cafe::/64

## Partition 6
### V4: 10.90.160.0/19
### V6: fdef:1337:f50f:cafe::/64

## Partition 7
### V4: 10.90.192.0/19
### V6: fdef:1337:f60f:cafe::/64

## Management / Internal Networks
### V4 10.90.224.0/19

* 10.90.224.0/22 : RZ FRA
  * 10.90.224.0/24 : Management RZ
    * 10.90.224.1 : Gateway
    * 10.90.224.11 : xsffr1
    * 10.90.224.12 : xsffr2
    * 10.90.224.21 : xsffr1-bmc
    * 10.90.224.22 : xsffr2-bmc
  * 10.90.226.0/24 : Admin VPN
* 10.90.240.0/20 : Wireless Backbone
  * 10.90.240.0/22 : Transfer
  * 10.90.250.0/24 : Admin VPN
  * 10.90.252.0/23 : Management
  * 10.90.255.0/24 : Loopback
