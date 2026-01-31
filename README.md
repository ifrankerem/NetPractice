*This project has been created as part of the 42 curriculum by iarslan.*

# NetPractice

## Description
NetPractice is a practical networking exercise where you learn the fundamentals of TCP/IP addressing by fixing small network diagrams (10 levels).
Your goal in each level is to make the simulated network work by configuring IP addresses, subnet masks, and default gateways, while understanding the roles of routers and switches.

The networks are simulated. You solve each level using a local training interface opened in a web browser.

## Instructions

### 1) Open the interface
- Open `index.html` in your browser (Chrome/Chromium recommended).
- Choose:
  - **Training**: uses your intranet login
  - **Evaluation**: generates random levels (used in defenses)

### 2) Solve levels
- Read the goal at the top of the page.
- Edit only the **unshaded** fields.
- Use:
  - **Check again** to validate
  - **Logs** to understand mistakes (invalid IP, wrong mask, missing gateway, etc.)

### 3) Export configs (required)
After finishing **each** level:
1. Click **Get my config**
2. Save the exported config file
3. Repeat for all **10 levels**

## Submission Details
As per the project requirements, 10 exported configuration files (one for each level) are placed at the root of this repository.

## Resources

### Networking Fundamentals (Playlist)
  
  https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi

I learned networking fundamentals in this playlist such as. TCP/IP addressing, default gateways, network devices such as repeater, hub, bridge, switch, router. Also ı learned OSI layers in this playlist. How a host communicate within same network and outside of his network.

- IP (Internet Protocol) =  It is a set of rules that determines how data is exchanged over the internet.”

- IP Address = An IP address is a number that identifies a device on a network. These addresses are just 32 bit numbers.

- Host = These are any device which sends or receive packets or data.

- Network = A network carries packets between hosts.

- Subnet = Networks can contain other networks.

- Subnet Mask = A subnet mask divides an IP address into parts.

- Default Gateway = A device sends data to the default gateway when the destination is not in the same network.

- MAC Address = A MAC address is a unique hardware address of a network device (or network card). It is used to identify devices inside a local network (LAN).

- Switches = A switch connects devices in the **same** local network and forwards data to the correct device using MAC addresses.”

- Router = A router connects different networks and sends packets **between** them.

- Modem = A modem is a device that converts digital data (0s and 1s) into signals that can travel through the internet line, and converts those signals back into digital data.

- Repeater = A repeater is a device that repeats and boosts a signal to extend the network range.

- Hub = Simply multi-port repeaters.

- Bridge = A bridge connects two parts of a local network and forwards data between them. For example between two hubs.

- OSI Layers = The OSI model is a 7-layer system that explains how data moves from one device to another in a network.
	#### Layers
	1. Physical  
	2. Data Link  
	3. Network  
	4. Transport  
	5. Session  
	6. Presentation  
	7. Application  

- TCP = TCP is a transport protocol that sends data reliably. It makes sure the data arrives in order and retransmits lost data.

- UDP = UDP is a transport protocol that sends data faster and simpler, but it does not guarantee delivery or order.

- ARP Protocol = ARP is a protocol that finds the MAC address of a device using its IP address on a local network.

- DNS = DNS translates website names (domain names) into IP addresses.

### Subnetting (Playlist)  
  https://www.youtube.com/watch?v=BWZ-MHIhqjM&list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE
  
I learned subnetting math in this playlist. How ı can part a network to sub networks. Whats CIDR, Network ID, Broadcast IP ...

- Network ID = The network address of the subnet. It represents the subnet itself (not for devices).
- Broadcast IP: The address used to send data to all devices in the subnet (not for devices). For example DHCP process.

### How the Internet Was Created 
  https://www.youtube.com/watch?v=VPToE8vwKew

I learned internet history in this video.how early networks worked, and how it grew into a global system. It explains ideas likes **Packet Switching**, **ARPANET**, **DNS** , **WORLD WIDE WEB**, **INTERNET SERVICE PROVIDERS**, **First Web Site: https://info.cern.ch/** how different networks became connected to form today’s Internet.


### My Excalidraw

https://link.excalidraw.com/readonly/W3v39dKaJFCpCF2shnkR

Here is my excalidraw link. When i learned these topics ı noted all my work here so if anybody want to know and need notes he/she can look at it.


## AI Usage 
- I did not use AI while solving the levels. I made the IP/mask/gateway decisions myself and verified them using Check again and the Logs inside the project.
- After finishing the levels, I used AI to **learn more deeply**: exploring **alternative valid configurations**, understanding *why* certain solutions work, and reinforcing subnetting/gateway concepts.
- AI output was used as a learning aid and always checked against networking rules and the simulator behavior.