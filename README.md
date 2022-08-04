# Smurf Attack

## ICMP

Internet Control Message Protocol (ICMP) is used for reporting errors and performing network diagnostics.

## How ICMP work
The ICMP ping process is a way to test if two devices on the network can connect to each other. It can also be used to check for packet loss and delay within a network. The ping command transmits a request for an ICMP echo to a network device. That device then replies right away with an ICMP echo. 

## Smurf Attack

A smurf attack is a type of denial of service attack in which a system is flooded with spoofed ping messages. This creates high computer network traffic on the victim’s network, which often renders it unresponsive.



## Working of Smuarf Attack

- First, the malware creates a network packet attached to a false IP address — a technique known as "spoofing."
- Inside the packet is an ICMP ping message, asking network nodes that receive the packet to send back a reply
- These replies, or "echoes," are then sent back to network IP addresses again, setting up an infinite loop.
