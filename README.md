# net_practice
The goal of this project was to familiarize ourselves with IP addressing within the TCP/IP model. We had to configure the IP adresses and network masks of 10 simulated networks with routers, switches, a internet gateway and computers.
![Level 3](https://raw.githubusercontent.com/WaPoco/net_practice/main/net_practice.1.6/net_practice/netpractice.png)

# What is TCP/IP model?
It's a framework of protocols that ensures the transmission of data across networks (including the internet). The communication protocols are organized in 4 layers of different purpose: **Application, Transport, Internet, and Network Access**.

**Application Layer**

Consists of different protocols that are necessary to communicate between applications across a network:  

- **Web**: Browser ↔ Webserver (`HTTP`, `HTTPS`)  
- **Email**: Mail client ↔ Mail server (`SMTP`, `IMAP`, `POP3`)  
- **File transfer**: Client ↔ Server (`FTP`, `SFTP`)  
- **Remote connection**: Admin ↔ Server (`SSH`)  


***Transport layer***:

Protocolls that ensures delivery of data packets between applications on different devices:
Most common are TCP or UDP. TCP is more reliable because it ensures the delivery of data packets. On the other side UPD (User Datagram protocol) is faster but doesn't garantee the arrival in the rigth order. The use cases for UDP: Streaming (video/audio), online gaming, VoIP, DNS.

**Internet layer**:

takes care of the adressing and routing with the IP protocoll

**Network access layer**:

physical transmission (Wi-fi, ethernet)
### Example:

You watching a video on a website.

Application layer: HTTPS

Transport layer: UDP

# What is TCP?
The Transmission Control Protocol (TCP) is set of rules that governs how computers communicate reliably over a network. Therefore it breaks data into small packets, sends them over the network and ensures they are delivered error free and in the correct order at the recipient.

# What is the IP?
The **Internet protocoll (IP)** is a protocoll and used for routing and addressing across networks. In **IPv4** an address is a **32-bit** long number and is divided into **4 octets** (8-bit-segments).

"number1.number2.number3.number4" or "XXXXXXXX.XXXXXXXX.XXXXXXXXX.XXXXXXXXX"
```198.98.23.23``` or ```11000110.1100010.00010111.00010111```

all number in the range 0-256

For example:
| Class | IP Range|
|-------|--------------------------|
|class A| 10.0.0.0 - 10.255.255.255|
|class B| 172.16.0.0 - 172.31.255.255|
|class C| 192.168.0.0 - 192.168.255.255|

local ip for internal use:
127.0.0.1 127.255.255.254

# What is the subnet mask?
The subnetmask is a 32 bit long number and useful to calculate the ip range .

What is subnetting?
What is a router?
What is IP forwarding?
What is the broadcast address?
