# NetPractice (42Porto - 42Cursus)   

## Grade: 100/100

###  Subject: [NetPractice en_subject](./extras/en.subject_netpractice.pdf)

###  About:

### Useful links:  
General understanding:  
https://youtu.be/tSodBEAJz9Y  
https://youtu.be/eMamgWllRFY  
https://www.youtube.com/watch?v=_IOZ8_cPgu8  
What is DNS?: https://www.youtube.com/watch?v=Rck3BALhI5c  
How DNS works: https://www.youtube.com/watch?v=uOfonONtIuk  
Routers vs. Switches vs. Access Points: https://www.youtube.com/watch?v=Vc16CCAAz7Q  
Network Basics: https://www.youtube.com/watch?v=_IOZ8_cPgu8  

Network Protocols:  
https://youtu.be/E5bSumTAHZE  
What is TCP/IP?: https://www.youtube.com/watch?v=PpsEaqJV_A0  
TCP/IP in Computer Networking: https://www.geeksforgeeks.org/tcp-ip-in-computer-networking/  

https://www.youtube.com/watch?vs=aor29pGhlFE  

TCP vs UDP: https://www.youtube.com/watch?v=uwoD5YsGACg  
What is DHCP?: https://www.youtube.com/watch?v=e6-TaH5bkjo  

What is a loopback address?: https://www.geeksforgeeks.org/what-is-a-loopback-address/  

What makes and IP Address invalid?:  
https://smallbusiness.chron.com/teredo-firewall-64039.html  
https://www.quora.com/How-do-you-identify-an-invalid-IP-address  

Reserved IP Addresses: https://en.wikipedia.org/wiki/Reserved_IP_addresses  

What is Routing: https://www.cloudflare.com/learning/network-layer/what-is-routing/  
What is a Routing Table: https://www.geeksforgeeks.org/routing-tables-in-computer-network/  

Subnet CheatSheet:  
https://www.freecodecamp.org/news/subnet-cheat-sheet-24-subnet-mask-30-26-27-29-and-other-ip-address-cidr-network-references/  

##### Notes:

Hosts - Any device that sends or receives traffic  
Every host needs 4 items for Internet Connectivity:  
    IP Adress - Host's identifier on the internet  
    Subnet mask - Size of Host's network  
    Default Gateway - Router's IP Address  
    DNS Server's IP - Translates domain names to IP Adresses  

LAN - Local Area Network  

WAN - Wide Area Network  
    -> Connects separate LANs together  

MAC adresses -  
    -> Layer 2 adresses  

IP adresses -  
    -> Layer 3 adresses  

Protocols:  
Network Protocol: Set of Rules and Messages that form an Internet Standard  

ARP - Adress Resolution Protocol  
    -> Resolves IP to MAC mappings    https://www.youtube.com/watch?v=PpsEaqJV_A0
    -> ARP Requests / ARP Responses  

FTP - File Transfer Protocol  
    RETR <-> file  
SMTP - Simple Mail Transfer Protocol  
    HELO <-> 250  
HTTP - Hyper Text Transfer Protocol  
    GET <-> 200 OK  

SSL - Secure Sockets Layer  
TLS - Transport Layer Security  
HTTPS - HTTP secured with SSL/TLS  

DNS - Domain Name System  
    -> Translate a domain name into its IP address. Internet's version of Yellow Pages    
    IP of site.com? <-> IP of site.com  

DHCP - Dynamic Host Configuration Protocol  
    -> Provides IP, Subnet Mask, Default Gateway and Domain Name Server for clients  

What's an IP?  
IP - Internet Protocol  
    -> Dictates how things are delivered and permits optimizing the transfer route  

TCP/IP - Transmission Control Protocol / Internet Protocol  
    TCP:  
    Connection oriented protocol  
    -> **Guarantees** that all the data is **received** and **in order** thru a  
    3-way handshake:  
        - A computer will send a message called a SYN (SYN ->)
        - The receiver computer will send back an acknowledgement message (<- SYN ACK)
        - The sender computer sends back an acknowledgment message (-> ACK RECEIVED)
    For each segment in transit, the sender keeps a timer. If the timer ends before an ACK  
    for the segment is received, the message is resent.  
    Use cases: Downloading files, viewing webpages, etc. Anything that must be 100% correct  

UDP - User Datagram Protocol  
    Connectionless oriented protocol (doesn't establish a session and therefore can't guarantee that all the data arrives with integrity), faster than TCP for this fact
    Use cases: streaming video/audio Anything that it's ok if a little thing doesn't arrive 100% correct


IPv4 - 32bit 
IPv6 - 128bit, no backwards compatibility

DNS - 




Concepts per level:  
Level 01:  
Routers set a local IP Address, so, they must be the same until the last field (which has to be of the same length (?))

Level 02:  
    Subnetting, masks, number of available IP Addresses
    x.x.x.1 (?)

Level 03:  
    Switch sends the input to every host on LAN  

Level 04:  
    ?

---
Made by Nuno Carvalho (Kuninoto) | nnuno-ca@student.42porto.com  
<div id="badge"> <a href="https://www.linkedin.com/in/nuno-carvalho-218822247"/> <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>&nbsp;
