[README.md](README.md#sub-section)
# Task 2:
   Analyse a suspicious piece of network traffic captured in pcap file.


+ Which systems (i.e. IP addresses) are involved?<br>
ip: source: 98.114.205.102<br>     destination: 192.150.11.111
![This is an image](/assets/images/ip-source-destination.png)


+ What can you find out about the attacking host (e.g., where is it located)?

https://iplocation.net/ip-lookup or the command whois ( Ubuntu 20.04)

   When a host is infected or otherwise compromised, security professionals need to quickly review packet captures (pcaps) of suspicious network traffic to identify affected hosts and users.

   This tutorial offers tips on how to gather that pcap data using Wireshark, the widely used network protocol analysis tool. It assumes you understand network traffic fundamentals and will use these pcaps of IPv4 traffic to cover retrieval of four types of data:

      1) Host information from DHCP traffic
      2) Host information from NetBIOS Name Service (NBNS) traffic
      3) Device models and operating systems from HTTP traffic
      4) Windows user account from Kerberos traffic
      
+ How many TCP sessions are contained in the dump file?
![This is an image](/assets/images/conversations.png)
There are 5 conversation on the run.
+ How long did it take to perform the attack?

   16 seconds
+ Which operating system was targeted by the attack? And which service?

+ Which vulnerability?

+ Can you sketch an overview of the general actions performed by the attacker

+ Which are the protocols involved? What can you tell about the payload?
