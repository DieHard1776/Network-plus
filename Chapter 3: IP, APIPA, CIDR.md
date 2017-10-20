Definition: DHCP: Dynamic Host Configuration Protocol is a standardized network protocol used on Internet Protocol (IP) networks

I/ IP
-----

IP address are logically mapped to Physical address

An Internet Protocol address (IP address) is a numerical label assigned to each device (e.g., computer, printer) participating in a computer network that uses the Internet Protocol for communication

Ip address can point to one computer one day and next day can point to a completely different computer

Ip address is are logically address so they can change. A computer could have multiple IP address because we move between different network. The IP address is provided to our computer by the network we're on.

There are 2 types of IP

IP LAN : 192.168.xxx.xxx
 
IP public of Modem  go to what is my IP to check

*CLASS:
Class A: 1- 126.
Class B: 128-191
Class C: 192-223

127: local host
IF We ping 127.0.0.1 we ping our self, we ping our own NIC
Class D: Multicasting 224- 239

II/ APIPA 
/pronounce: a pi bar/

APIPA: automatic public IP addressing
APIPA is an address that is automatically assigned to our computer for an IP address when it doesn;t receive any DHCP information
Our computer received Ip address information from DNS information, default gateway information...( computer receives information it needs to assign the IP address), when our computer not received these information or when it doesn;t have static IP address, this is where APIPA comes in.
APIPA will automatically assigned us IP address: 169.254.x.x

SO when working normally, we get APIPA address, (169.254.x.x) , it means some part of our network liek router, DHCP,... is wrong, because that;s why we get APIPA address, instead of other IP address

Tip: open Command prompt -> type "IPconfig"


III/ Public vs Private address

* Public IP address

Everyone in the world can reach us because the public IP address is the single unique IP address for a computer somewhere in the world. 

Public IP address is globally routable, you can reach public IP address around the globe.

We give devices private IP address so that IP address won;t run out....

The router, that we use to connect to have private IP for each devices, does has public IP address. The Internet services provider may swap this IP address, or you may have the reserved public IP address

*Private Ip address range
class A 10.0.0.0 -> 10.255.255.255
class B 172.16.0.0 -> 172.31.255.255
class C 192.168.0.0 -> 192.168.255.255

Dynamic IP: 2 types: IP LAN và IP Public

IV/ CIDR 
pronounce: CIDR : /ˈsaɪ.der/ :Classless inter Domain Routing
With classful routing, we have class A, class B, class C routing with default subnet mask for each class

CIDR notation:  CIDR notation is a compact representation of an IP address and its associated routing prefix

For example:

192.168.100.14/24 represents the IPv4 address 192.168.100.14 and its associated routing prefix 192.168.100.0, or equivalently, its subnet mask 255.255.255.0, which has 24 leading 1-bits.

V/ IPv4 vs IPv6

IPv6: 128 bit: Internet protocol version 6
=> use Hexadecimal
seperated in 32 set of 4 hexadecimal character 

VI/ Unicast, Multicast
Unicast
Unicast address is the address that specify one single computer

Multicast: 1-> many








