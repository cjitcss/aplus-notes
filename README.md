# CompTIA A+ exam preparation notes
Feel free to help out :)
<br>
### Troubleshooting Methodology

1. Identify the problem.
2. Establish a theory of probable cause (question the obvious).
3. Test the theory to determine cause.
4. Establish a plan of action to resolve the problem and implement the solution.
5. Verify full system functionality, and implement preventive measures.
6. Document findings, actions, and outcomes.

**To remember the order**: *I Eat Tacos Every Valentine's Day*

### Ports and protocols
| Port # | Abbreviation | Protocol                           | Connection Type     
|--------|--------------|------------------------------------|---------------------
| 20     | FTP Data     | File Transfer Protocol (Data)      | Connection-oriented  
| 21     | FTP          | File Transfer Protocol             | Connection-oriented   
| 22     | SSH          | Secure Shell                       | Connection-oriented  
| 23     | Telnet       | Telnet                             | Connection-oriented   
| 25     | SMTP         | Simple Mail Transfer Protocol      | Connection-oriented  
| 53     | DNS          | Domain Name System                 | Connectionless       
| 67     | DHCP Server  | Dynamic Host Configuration Protocol (Server) | Connectionless           |
| 68     | DHCP Client  | Dynamic Host Configuration Protocol (Client) | Connectionless           |
| 80     | HTTP         | Hypertext Transfer Protocol        | Connection-oriented  
| 110    | POP3         | Post Office Protocol v3            | Connection-oriented   
| 137    | NetBIOS Name | NetBIOS Name Service               | Connectionless       
| 139    | NetBIOS Session | NetBIOS Session Service          | Connection-oriented  
| 143    | IMAP         | Internet Message Access Protocol   | Connection-oriented 
| 161    | SNMP         | Simple Network Management Protocol | Connectionless       
| 162    | SNMP Trap    | SNMP Trap                         | Connectionless       
| 389    | LDAP         | Lightweight Directory Access Protocol | Connection-oriented 
| 443    | HTTPS        | Hypertext Transfer Protocol Secure  | Connection-oriented   
| 445    | SMB          | Server Message Block               | Connection-oriented 
| 3389   | RDP          | Remote Desktop Protocol            | Connection-oriented  

 **Computer networks**

| |   |
| ------------ | ------------ |
|**PAN**   |Personal Area Network   |
|**LAN**   |Local Area Network   |
|**MAN**   |Metropolitan Area Network   |
|**WAN**   |Wide Area Network   |


### **Wi-Fi standards**

|Standard   |Frequency   |Maximum speed      | Features |
|------------ | ------------ | ------------ | ------------ |
|**802.11a**   |5 GHz    |54 Mbit/s   |
|**802.11b**   |2.4 GHz      |11 Mbit/s   |
|**802.11g**   |2.4 GHz   |54 Mbit/s   |
|**802.11n** (Wi-Fi 4)   |2.4 GHz / 5 GHz   |600 Mbit/s   | MIMO
|**802.11ac** (Wi-Fi 5)  |5GHz   |6.9 Gbit/s   | MU-MIMO
|**802.11ax** (Wi-Fi 6)   |2.4 GHz / 5 GHz   |9.6 Gbit/s   |MU-MIMO, OFDMA


### **Wi-Fi antennas**

| Name|Direction   |
| ------------ | ------------ |
|Yagi   | Point-to-point  |
|Dish   |Point-to-point    |
|Panel   | Point-to-point   |
|USB Wi-Fi   |Omni-directional   |


### **PoE**

| |   |
| ------------ | ------------ |
|**802.3af**   | PoE   |
|**802.3at**   |PoE+   |
|**802.3bt**   |PoE++   |

### DHCP
**DORA**
1. Discover
2. Offer
3. Request
4. Acknowledge

**APIPA** - Automatic Private IP Addressing


### DNS

| Record|Description   |
| ------------ | ------------ |
|**A**   | IPv4  |
|**AAAA**   |IPv6   |
|**MX**   | Mail exchanger   |
|**TXT**  | Text record   |

Spam management:
- DomainKeys Identified Mail (**DKIM**)
- Sender Policy Framework (**SPF**)
- Domain-based Message Authentication, Reporting, and Conformance (**DMARC**)
