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

## Partition 8 (Wireless Backbone)
### V4: 10.90.224.0/19
* Transfer: 10.90.248.0/22 [je /30]
  * 10.90.248.0/30 : FAN <-> Zeiss
  * 10.90.248.4/30 : FAN <-> Isar
  * 10.90.248.8/30 : Zeiss <-> Galeria
  * 10.90.248.12/30 : KHG <-> Galeria
  * 10.90.248.16/30 : KHG <-> Isar
* Admin-VPN: 10.90.252.0/24 
* Management: 10.90.254.0/24
  * 10.90.254.11 : pbe-fan-1
  * 10.90.254.12 : pbe-fan-2
  * 10.90.254.21 : pbe-khg-1
  * 10.90.254.22 : pbe-khg-2
  * 10.90.254.31 : pbe-zeiss-1
  * 10.90.254.32 : pbe-zeiss-2
  * 10.90.254.33 : nbe-zeiss-3
  * 10.90.254.41 : pbe-isar-1
  * 10.90.254.42 : pbe-isar-2
  * 10.90.254.51 : pbe-galeria-1
  * 10.90.254.52 : pbe-galeria-2
* Loopback: 10.90.255.0/24 [je /32]
  * 19.90.255.1 : erx-fan
  * 10.90.255.2 : erx-khg
  * 10.90.255.3 : erx-zeiss
  * 10.90.255.4 : erx-isar
  * 10.90.255.5 : erx-galeria

### V6: fdef:1337:f70f:cafe::/64
