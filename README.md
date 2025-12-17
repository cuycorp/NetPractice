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
i.e.
255.255.255.224 ~= /27 (CIDR Mask)
* Default gateway
* Switches: facilitate communication within a network. Switched can have multiple ports and have the information of which host are on each port.
* Routers: 
    ....* facilitate communication between networks. It knows in which interface their devices are connected, which means it had an IP address that knows to which network its attached to.
    ....* Hosts connected to a router interface must use the same subnet mask as that interface, while different router interfaces may use different masks because they belong to different network
* Repeater: regenerate signal
* OSI layers

- Calcualtor of IP address given a mask: https://cidr.xyz/

https://youtu.be/H7-NR3Q3BeI?si=wf484ZlvCfPmbQit
