# NetPractice

*This project has been created as part of the 42 curriculum by <mcamaren>.*

# Networking Training Project

## Description

This project is an **interactive networking training interface** designed to practice and validate fundamental networking concepts through progressive levels.

The goal of the project is to help students understand and apply core networking principles:

 * IP addressing
 * Subnet masks
 * Routing
 * OSI model
 
 by solving practical configuration challenges. Each level focuses on a specific concept or combination of concepts, reinforcing both theoretical knowledge and hands-on problem solving.

The project consists of a browser-based training interface where users configure network elements and export their solutions for evaluation.

## Instructions

### Running the Training Interface

1. Clone the repository:
   ```bash
   git clone <repository_url>


## Resources

* Host: device that send or receives traffic. 

* TCP/IP addressing
* Network: grouping of hosts that require similar connectivity. Hosts on a network share same IP address space e.g. 192.168.1.x
* Subnet mask: separate network from host part
    * i.e. 255.255.255.224 ~= /27 (CIDR Mask)
    * choosing an adequate mask: 
        1. Count the required IPs
        2. Pick smallest mask that fits
        3. Verify the mask respect API ranges
* Default gateway
* Switches: 
    * Facilitate communication within a network. 
    * Switches can have multiple ports and have the information of which host are on each port.
    * Devices connected to it share mask and IP adress space e.g. 192.168.1.x
* Routers: 
    * Facilitates communication between networks. It knows in which interface their devices are connected, which means it had an IP address that knows to which network its attached to.
    * Hosts connected to a router interface must use the same subnet mask as that interface, while different router interfaces may use different masks because they belong to different network
    * Network routes: 
        * default = 0.0.0.0 and gateway = Router's IP on the same network
        * You can have specific routes for certain networks, but typically hosts use a default route to send everything to the router, which then makes more intelligent routing decisions.

* Repeater: regenerate signal
* OSI layers

- Calcualtor of IP address given a mask: https://cidr.xyz/

https://youtu.be/H7-NR3Q3BeI?si=wf484ZlvCfPmbQit


## Theory b level

1. Level 1
    * Mask * IP --> Subnet
    * Consider range: limits ]CIDR Base IP, Broadcast IP[
2. Level 2
    * Networks share mask
3. Level 3
    * Switch 
4. Level 4
    * Router
5. Level 5
    * Host-specific routing: rule to send information that is not going inside the network
6. Level 6
    * 
