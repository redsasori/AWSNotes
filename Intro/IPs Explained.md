## 2 Types :
IPV4 & IPV6

Note: These are like phone number, also they can use only a certain range of numbers.

Range:
IPV4 : 0.0.0.0 to 255.255.255.255

Example: reddit.com -> 192.254.236.136

## Classes of IPV4:
A,B,C,D,E -> Class D is reserved for Multicasting addressing, Class E is reserved for Experimental purposes.

Class A -> 1.0.0.0. to 126.255.255.255
Class B -> 128.0.0.0 to 191.255.255.255
Class C -> 192.0.0.0 to 223.255.255.255

127.0.0.1   -> Loopback address (It pings it's own device) 

## RFC1918 -> Private and Public IPs. 

https://www.rfc-editor.org/rfc/rfc1918.html

Private Address Space:
The Internet Assigned Numbers Authority (IANA) has reserved the
   following three blocks of the IP address space for private internets:

     10.0.0.0        -   10.255.255.255  (10/8 prefix)
     172.16.0.0      -   172.31.255.255  (172.16/12 prefix)
     192.168.0.0     -   192.168.255.255 (192.168/16 prefix)

Private IPs are used in Closed Infrastructure/ offices.

R3 Devices/Gateways(Cloud) -> Whenever a device from closed infra requires information from the internet it will go through the r3 device/gateway(It will have its own public ip/ our private ip of the device wont be disclosed). 

## Network Address Translation 

Closed Infra device(Private IP) -> R3/Gateway -> ISP -> Internet

