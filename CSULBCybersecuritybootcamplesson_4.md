---
title: CSULBCybersecuritybootcamplesson 4
created: '2021-11-17T02:11:32.450Z'
modified: '2021-11-17T03:10:17.523Z'
---

# CSULB_Cyber_security_bootcamp_lesson 4

## network traffic 
  - data packets 
    - like a road system
  - routers and swtiches 
    -are like the traffic lights 

## switches 
  - the switch handles traffic in a sub-network
  - switches use mac address to route traffic 
  - if the mac address is not present the switch sends it to the router 
  - the router uses the ip address to find where to send it to
  - both use router tables do store the data of the ip and mac address 
  - un mangered is plug and play takes all mac addys
  - managed you have to assign the mac address's 

  ## router and switch port security 

    - switch port security
      - protects against mac flood 
    - look up mac flooding 
    - routers use a acl or acess control list 


# protocols

 ## icmp 

    - internet control message protocol 
    - ping command uses icmp

## ping flood
- someone is constanly pinging a network 
- involves large amounts of icmp requests
- causes a DoS attack denail of service
- There are also DDoS attacks wich is a DoS attack with more attackers

## traceroute 

 - a tool used to map networks
 - used for trouble shooting 
 - determins the path to the destination 
 - series of astriks means the network is down or not responding.
 
 ## dns 

 - service used to translate ip address to domain name
 - ns look up is the command to look up the dns
 - dns is saved on the home router 
 - many companies have security services based on public DNS 
 -
## dns protection
- dnssec 
  - makes you provide credtiaols 
- dns poisoning
  - taking over the dns server and redirecting traffic

## browsers 
- http is sent in plain text 
- https is encrypted 
- webrosers are html css and javascript ides 

## https
- defines how web content is exchanged 
- encrpytied 

## ip sec 
- information transferred across networks can be inspected 
- ipsec and https provide a secure way to communicate through authentication.


## url Uniform resouce locater 
- url format H
 - www.PROTOCOL://HOSTNAME:PORT/PATH
- urls can be malicious

## additional network commands

- arp (address resoultion protocol)

## virtualization 
- create a virutal operating system inside your own computer 
- used to contain software and to act as a test site

## virtualbox 

- free and open source 
- very robust 
- cross platform 
- can be used to create virtual networks 

## virtualization concepts 

## virutal box nat network 
- network traffic goes through host machine.
## virtual box  bridged network
- all network information is coming from the router itself 
## virtual box internal network
- all virutal machines are isolated from the network connection 

## virtual box snapshops 
- backups of virtualization data
- recommended for colatile work enviro
- can serve as restoration points

## virutal box hardware

- mother board - fallicates conection and flow of data
- CPU - the brain of a computer. 
- RAM - used for tempory data storage
- HDD - used for data storage (on disk moving atoms)
- SSD - used for data stoarge (transistors) 
look up how a HDD works 

## hardware types 
- input decives 
	- mouse keyboard joystick etc
- output devcies 
	- screens printers speakers
## software 
- a collection of instructions for a computer to process 


## windows os flavors 
- home 
	- basic features for individual use
- enterprise 
	- features suited to organization environments 
- server 
	- taliored to os service managment



