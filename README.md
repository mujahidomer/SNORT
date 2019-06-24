# STUDY & ANALYSIS OF SNORT
![](snort.png)

Malicious network traffic *(such as worms, hacking attempts, etc.)* has certain patterns to it. You could monitor your network traffic with a sniffer and look for this malicious traffic manually, but that would be an impossible task. **IDS** *(Intrusion Detection System)* software which automates the process of sniffing, examining, and upon finding something suspicious, alerting.

IDS have been called the burglar alarm of computer networks and are an important part of network perimeter security. Without IDS you have no idea if someone is probing or attacking your servers (unless the attack is so overwhelming that it results in a denial of service). Having this information can let you know if you need to make some firewall changes or harden the OS on a particular server a bit more. 

You may see the term IPS for Intrusion Prevention Systems which takes things one step further, having the IDS adjust the firewall when it discovers something. Smart people disagree on the use of IPSs as it, in effect, gives an attacker some control of your firewall. 

Snort ([www.snort.org](www.snort.org "www.snort.org")) is the most widely-used IDS software application and it's open source and included with Debian. **There are two flavors of IDS**s, 
- Host-based 
- Network-based.

Snort is a network-based IDS that can monitor all of the traffic on a network link to look for suspicious traffic. Typically, a network-based IDS is set up to monitor a DMZ or the internal network right behind the firewall so it alerts to any possible threats that your firewall didn't catch. 

There is a Web interface that works with Snort called BASE (Basic Analysis and Security Engine) which is based on ACID (Analysis Console for Intrusion Databases) which we'll set up. BASE uses what's commonly referred to as a LAMP server (Linux, Apache, MySQL, PHP) so we'll need to install those applications as well.

##### This project was a work of 3 people. Myself, Jamoliddin & Lakshay. It was submitted as a project in our 3rd year of B.Tech for the subject of CyberSecurity
