# net_practice
The goal of this project was to familiarize ourselves with IP addressing within the TCP/IP model. We had to configure the IP adresses and network masks of 10 simulated networks with routers, switches, a internet gateway and computers.

# What is TCP/IP model?
It's a framework with 4 layers.

-**Application layer** - Consist of different specific protocolls like FTP, HTTPS, HTTP, ... and on the application context (Website, Email, Files)

-**Transport layer** - Protocolls that ensures transmision of datapackets like TCP or UDP

-**Internet layer** - takes care of the adressing and routing with the IP protocoll

-**Network access layer** - physical transmission (Wi-fi, ethernet)
### Example:

You watching a video on a website.

Application layer: HTTPS

Transport layer: UDP

# What is TCP?
The Transmission Control Protocol (TCP) is set of rules that governs how computers communicate reliably over a network. Therefore it breaks data into small packets, sends them over the network and ensures they are delivered error free and in the correct order at the recipient.

# What is the IP?
The IP (Internet protocoll) is a protocoll  IPeV.4 is a 32 bit number which can described in different notatins.  

"number1.number2.number3.number4" or "XXXXXXXX.XXXXXXXX.XXXXXXXXX.XXXXXXXXX"

all number in the range 0-256

For example:
```198.98.23.23``` or ```11000110.1100010.00010111.00010111```
class A 10.0.0.0    10.255.255.255
class B 172.16.0.0  172.31.255.255
class C 192.168.0.0 192.168.255.255

local ip for internal use:
127.0.0.1 127.255.255.254

# What is the subnetmask?
The subnetmask is a 32 bit long number and useful to calculate the ip range .

What is subnetting?
What is a router?
What is IP forwarding?
What is the broadcast address?
