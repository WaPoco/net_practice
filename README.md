# net_practice
*This project has been created as part the 42 curriculum by vpogorel.*

# Description
The goal of this project was to familiarize ourselves with IP addressing within the TCP/IP model. We had to configure the IP adresses and network interfaces of 10 simulated networks with routers, switches and connected computers.
<p align="left">
<img src="https://raw.githubusercontent.com/WaPoco/net_practice/main/net_practice.1.6/net_practice/netpractice.png" width="1000" height="800">
</p>

## What is the TCP/IP model?
It's a framework of protocols that ensures the transmission of data across networks (including the internet). The communication protocols are organized in 4 layers of different purpose: **Application, Transport, Internet, and Network Access**.

**Application Layer**

Consists of different protocols that are necessary to communicate between applications across a network:  

- **Web**: Browser ↔ Webserver (`HTTP`, `HTTPS`)  
- **Email**: Mail client ↔ Mail server (`SMTP`, `IMAP`, `POP3`)  
- **File transfer**: Client ↔ Server (`FTP`, `SFTP`)  
- **Remote connection**: Admin ↔ Server (`SSH`)  


***Transport layer***:

Protocols that ensures delivery of data packets between applications on different devices:
Most common are TCP or UDP. TCP is more reliable because it ensures the delivery of data packets. On the other side UPD (User Datagram protocol) is faster but doesn't garantee the arrival in the rigth order. The use cases for UDP: Streaming (video/audio), online gaming or VoIP

***Internet layer***:

The Internet layer is responsible for the identification of computers within a network and the selection of the most efficient paths or routes between networks. The Internet Protocol (IP) provides for each device a unique 32 bit number (ip address). Based of the destination IP the protocol picks the most efficient paths to reach the destination host.
The core functionality of this layer are logical addressing (IP addressing), rounting (selecting the best path) and packet forwarding to the destination network. 

**Network access layer**:

physical transmission (Wi-fi, ethernet)

### Example:

You watching a video on a website.

Application layer: HTTPS

Transport layer: UDP

### What is TCP?

The Transmission Control Protocol (TCP) is set of rules that governs how computers communicate reliably over a network. Therefore it breaks data into small packets, sends them over the network and ensures they are delivered error free and in the correct order at the recipient.

### What is the IP and IP address?
The **Internet protocoll (IP)** is a protocoll and used for routing and addressing across networks. In **IPv4** an address is a **32-bit** long number and is divided into **4 octets** (8-bit-segments).

"number1.number2.number3.number4" or "XXXXXXXX.XXXXXXXX.XXXXXXXXX.XXXXXXXXX"
```198.98.23.23``` or ```11000110.1100010.00010111.00010111```
An IP address has a network and a host part. 

all number in the range 0-255.

For example:
| Class | IP Range|
|-------|--------------------------|
|class A| 10.0.0.0 - 10.255.255.255|
|class B| 172.16.0.0 - 172.31.255.255|
|class C| 192.168.0.0 - 192.168.255.255|

local ip for internal use:
127.0.0.1 127.255.255.254

### What is the broadcast address?
Broadcast address is the address that sends to every host of a network a message.

### What is the network address?
The network address is an unique identifier which will be assigned to each device in a network. 

### What is the subnet mask?
The subnetmask is a 32 bit long number and useful to calculate the network or host address of ip address.

### What is subnetting?
Subnetting describes the division of network into smaller subnetworks. Depeding of bits in the netmask you can devide the network into smaller networks.

### What is supernetting?

### What is a router and a default gateway?
A router is a network device that connects networks and routs data between them. It makes forwarding desicion based on the ip address and routing tables. A Internet Service Provider (ISP) assigns a public ip to the router in order to connect the local network (lan) to the internet.
...

When device wants to send a message to another network it has will send the message to the router (default gateway) which will look in the routing table for a the next hop.

### What is a switch?
A switch is device that forwards data to a mcadresses in a network.
### What is IP forwarding?

# Instructions



# Resources
