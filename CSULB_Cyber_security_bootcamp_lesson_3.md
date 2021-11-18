---
title: CSULB Cyber security bootcamp lesson 3
created: '2021-11-10T01:39:19.468Z'
modified: '2021-11-10T05:49:41.000Z'
---

# CSULB Cyber security bootcamp lesson 3

# network fundmentals 
no class thursday 

## internet back bone

- princlipal routes between large networks 
- owned by private and goverment companies or organizations 
  - ie cox, comcast, centruy link

## terminologys

- computers: client side
- sever: offers services and provides acces to data
- network: more than one endpoint device connect together 
- packet: a batch or "packet" of data that is sent out.
  - packets get sequnced together and then sent out to destination
- protocols: how is the information sent or rules for sending data

## basic network strcturedx

- computers are connected to swtiches for internal routing.
- routers communicate with the world wide web or between differnet routers. 

## client - sever connection
- client sends a request (get post 200)
- server ackndolges (ack) and sends response (post)

## lab 3
- dchp is how you get your ip 
- computers commuincate using an ip address
- dns server looks up the ip address for the specific domain 
- you can automatically set the ip or manually set it
- server side is usally manually set
- client side is usally automatic
- dhcp is how auto ip address are disbributed


## ip address
- idetify the computer
- ipv 4 is decimal value
- ipv6 is hexadecimal
- every end device must have an ip address to connect to a network
- ipv6 was created to address the shoratge
- diffenert classes of public ip address's

## ip format
- 4 divisions of octets
- 4 octets
- 1 octet = 8 bits
- 32 bits in ipv4 address's
- each octet can only be between 0 - 255


## subnetting
- a logical wa of grouping ip address's
- a building with rooms in it
- help determins the networks scope
  - ie this how big this subnet is 
- three classe's A,B,C
- last ip on a subnet network = broadcast address 
- a boardcast address is an address to send a message to the network


    Class A = 1.0.0.0 to 126.0.0.0
    Class B = 128.0.0.0 to 191.255.0.0
    Class C = 192.0.1.0 to 223.255.255.0


## subnet mask
- each octet is represented b binary digits (1's and 0's)
- subnet mask is what idetifies the network portion of the ip and the portion for the host's
- 

## class a subnet
- the first octet identifys the network scheme
- fewer networks, more host's
- default = 255.0.0.0
- /8 repesents class a because you use 8 bits

# class b subnet
- the first two octets are reseved for network idenity
- last two are resevered for host systems
- more networks then class a but fewer hosts than class a
- /16 represents class b because you use 16 bits

## class c subnet
- the first 3 octets are reseverd for network identiy 
- last octet is resverd for host systems
- least amount of hosts but more networks
- /24 represents class c because you use 24 bits 

## private ip addres's
- public ip's are assinged by isp's
- private ip address's are resevred for local networks
- NAT stands for Network address translation
- NAT is responablie for relaying your private ip to the public ip

## ip address config modes
- static config, ip is set and not changed automatically
- dynamic config sets ip automatically on a lease
- dhcp servers alloacte the ip address's

## mac address's 
- differnet from an ip address
- idetifys THE HARDWARE  a computer
- it is a PHYSICAL ADDRESS it is linked to somthing in th PHYSICAL WORLD
- a unique identifier wrtien in hexadecim form
- first half of a mac address is assinged to the manufacture,
- second half is the manufactues idetiy of the device 

## local host
- the computer communicates with itself 
- a defualt ip address of 127.0.0.1
- has  subnet mask of 2.55.0.0.0
- is used for testing systems in enviroments

nat is the network address translation,

virutal box network configuations are on the test 
look up NAT FUCKER

# cywar signup code 
- LB-CS-23
- cywar.hackeru.com









