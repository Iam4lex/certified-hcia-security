1. Which of the following is the correct sequence of the ransomware attack process?

    A. Intrusion -> Proliferation -> Theft -> Ransom  
    B. Proliferation -> Intrusion -> Theft -> Ransom  
    C. Intrusion -> Theft -> Spread -> Ransom  
    D. Theft -> Intrusion -> Spread -> Ransom  
  
    <details>
    <summary>Show Answer</summary>
    **Answer:** A. Intrusion -> Proliferation -> Theft -> Ransom
    
    **Answer Analysis:**
    - (1) Use phishing and malicious emails to intrude networks.
    - (2) After a host is intruded, various attack methods are used to spread in the target network to increase the number of controlled hosts.
    - (3) Steal data from controlled hosts and upload the data to a server controlled by attackers.
    - (4) Ultimately, one or more ransomware viruses are run to paralyze the target network for profit.
    </details>

2. Hackers or organizations use distributed denial of service (DDoS) attacks to access enterprise databases without identity authentication, causing data leakage.

    - Right
    - Wrong
    
    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong
    
    **Answer Analysis:**  
    A DDoS attack exhausts the network or system resources of the target server, interrupts or stops the services of the target server, and causes users to fail to access the server.
    </details>
3. Which of the following attacks are malformed packet attacks?

    A. Teardrop attack  
    B. Smurf attack  
    C. Land attack  
    D. Tracert packet attack  
    
    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABC
    
    **Answer Analysis:**  
    In a Tracert packet attack, an attacker uses the ICMP Timeout packet returned when the TTL is 0 and the ICMP Port Unreachable packet returned when the packet reaches the destination address to discover the path through which the packet reaches the destination address. In this case, the attacker can spy on the network structure.
    </details>

 4. Which of the following attacks are TCP flood attacks?

    A. SYN Flood  
    B. SYN+ACK Flood  
    C. FIN/RST Flood  
    D. ICMP Flood  
    
    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABC
    
    **Answer Analysis:**  
    TCP packets are classified into SYN, SYN+ACK, ACK, and FIN/RST. The SYN Flood, SYN+ACK Flood, and FIN/RST Flood are all types of TCP flood attacks, while the ICMP Flood is not.
    </details>

 5. A single-packet attack indicates that an attacker controls a large number of zombie hosts and sends attack packets to the target. As a result, the link on the target network is congested and system resources are exhausted. As a result, the target network cannot provide services for normal users.

    - Right
    - Wrong
    
    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong
    
    **Answer Analysis:**  
    A single-packet attack means that a host or server crashes by sending defective packets, or sends special control packets or scanning packets to probe the network structure to prepare for a real attack. It does not involve a large number of zombie hosts or network congestion.
    </details>

6. Which of the following protocols can dynamically map IP addresses to hardware addresses, that is, obtain the corresponding hardware address based on the known IP address?

    A. ICMP  
    B. IGMP  
    C. ARP  
    D. RARP  
    
    <details>
    <summary>Show Answer</summary>
    **Correct answer:** C
    
    **Answer Analysis:**  
    ARP (Address Resolution Protocol) implements dynamic mapping between IP addresses and hardware addresses, obtaining the corresponding hardware address based on the known IP address.  
    RARP (Reverse Address Resolution Protocol) implements dynamic mapping between hardware addresses and IP addresses, obtaining the corresponding IP address based on the known hardware address.
    </details>

7. Which of the following statements about TCP are correct?

    A. Connection-oriented  
    B. Unreliable  
    C. High overhead  
    D. The application layer is responsible for reliability.

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** AC
      
    **Answer Analysis:**  
    TCP (Transmission Control Protocol) provides connection-oriented and reliable byte stream services. Connection-oriented means that two applications using TCP must establish a TCP connection before exchanging data. TCP provides reliable transmission services through mechanisms such as acknowledgment, error checking, and data reassembly. However, these mechanisms introduce significant overhead. TCP is not unreliable; that characteristic applies to UDP (User Datagram Protocol). The application layer is not responsible for TCP's reliability; TCP itself ensures this through its own mechanisms.
    </details>

8. Which of the following statements about the differences between MAC addresses and IP addresses are correct?

    A. A MAC address is a 48-bit physical address fixed on the device hardware and cannot be modified.  
    B. An IP address is a 32-bit address at the network layer and can be modified.  
    C. IP addresses are classified into public addresses and private addresses. Public addresses are globally unique, while private addresses can be reused within a LAN.  
    D. The MAC address can be defined by common users and can be modified.

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABC

    **Answer Analysis:**  
    An IP address is a 32-bit logical address, not a hardware address. A hardware address, such as a 48-bit MAC address, is fixed in the network interface card (NIC) and used for communication between devices on the same link. The MAC address is globally unique, whereas IP addresses can be either public or private. Public IP addresses are globally unique, while private IP addresses can be reused within a LAN. The MAC address cannot be easily modified by common users.
    </details>
9. IGMP is a management protocol and provides information services for IP. IGMP messages are carried in IP packets.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    ICMP (Internet Control Message Protocol) is a management protocol and provides information services for IP. ICMP messages are carried in IP packets. IGMP (Internet Group Management Protocol) is used for managing multicast group memberships and operates differently from ICMP.
    </details>
10. The TCP/IP protocol stack can be divided into seven layers, which are independent of each other.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    The TCP/IP protocol stack consists of five layers, not seven. The OSI (Open Systems Interconnection) reference model consists of seven layers. The layers in the TCP/IP model are: Application, Transport, Internet, Network Interface, and Physical. The layers in the OSI model are: Application, Presentation, Session, Transport, Network, Data Link, and Physical.
    </details>
    
11. Which of the following options record the connection status of TCP, UDP, and ICMP protocols, which is an important basis for the firewall to forward packets?

    A. Routing Table  
    B. MAC address table  
    C. ARP table  
    D. Session table

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** D

    **Answer Analysis:**  
    The firewall uses the session table to record the connection status of TCP, UDP, and ICMP protocols. This table helps the firewall track and manage ongoing sessions, allowing it to forward packets based on their connection status. A session represents the connection status between two communication parties on the firewall.
    </details>

12. Which area can be regarded as receiving the packets that need to be responded to and processed by the firewall (not forwarded)?

    A. Trust  
    B. DMZ  
    C. Untrust  
    D. Local

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** D

    **Answer Analysis:**  
    The Local zone, provided by the firewall, represents the firewall itself. This zone is used for handling packets that need to be responded to and processed by the firewall, rather than forwarded. Due to its unique role, security policies between the local zone and itself often need to be configured for applications requiring the device to send and receive packets.
    </details>

13. Which of the following zones is not the default security zone of the firewall?

    A. Trust  
    B. DMZ  
    C. Untrust  
    D. ISP

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** D

    **Answer Analysis:**  
    The default security zones of Huawei firewalls are Local, Trust, DMZ, and Untrust. The ISP zone is not a default security zone for these firewalls.
    </details>
14. The basic design principle of the firewall is that the traffic that is not explicitly permitted is allowed by default.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    The basic design principle of a firewall is that traffic not explicitly allowed is discarded by default. This principle ensures that only permitted traffic is allowed through, thus protecting the network from unauthorized access and potential threats.
    </details>

15. On Huawei firewalls, each security zone has a unique priority. The default priority of the Trust zone is 50.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    On Huawei firewalls, the default priority of the Trust zone is 85, not 50. The DMZ zone has the default priority of 50. This priority system helps determine the level of trust assigned to different zones within the firewall configuration.
    </details>

16. Which of the following NAT is applicable to the scenario where users access private servers through public addresses?

    A. NAT NO-PAT  
    B. NAPT  
    C. Easy IP  
    D. NAT Server

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** D

    **Answer Analysis:**  
    NAT Server, also called static mapping, translates the destination IP address of a packet. It provides the mapping between public and private IP addresses and translates the public IP address in the packet into the corresponding private IP address.
    </details>

17. Which of the following options is a private IP address?

    A. 1.1.1.1  
    B. 10.1.1.1  
    C. 100.1.1.1  
    D. 200.1.1.1

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B

    **Answer Analysis:**  
    Private IP addresses are reserved for use within private networks and are not routable on the public internet. The ranges for private IP addresses are:
    - **Class A:** 10.0.0.0 to 10.255.255.255
    - **Class B:** 172.16.0.0 to 172.31.255.255
    - **Class C:** 192.168.0.0 to 192.168.255.255
    
    Therefore, the IP address **10.1.1.1** falls within the private range specified for Class A.
    </details>

18. Which of the following NAT technologies are source NAT technologies?

    A. NAT No-PAT  
    B. NAPT  
    C. Easy IP  
    D. NAT Server

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABC

    **Answer Analysis:**  
    No-Port Address Translation (NAT No-PAT) translates only addresses and does not translate ports. In this way, one-to-one private address and one-to-one public address are translated. Easy IP: The implementation principle of Easy IP is the same as that of NAPT. Easy IP translates IP addresses and transport-layer ports at the same time. The only difference is that Easy IP does not have the concept of address pool and uses the public IP address of the outbound interface as the translated address.
    </details>

19. Common NAT translates not only the network layer and transport layer information, but also the IP address and port number carried in the application layer.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    NAT ALG is an application-level gateway (ALG) proxy that translates the IP address and port number carried in the application-layer data.
    </details>

20. Which of the following protocols is used to dynamically backup the status data and key configuration commands between the two firewalls?

    A. HRP  
    B. VRRP  
    C. VGMP  
    D. IGMP

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** A

    **Answer Analysis:**  
    The HRP protocol is used to dynamically back up the status data and key configuration commands between the two firewalls. The backup contents include configuration backup and status information.
    </details>

21. Which of the following states are the status of the firewall heartbeat interface?

    A. Invalid  
    B. Down  
    C. Running  
    D. Full

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABC

    **Answer Analysis:**  
    An HRP heartbeat interface has five states: Invalid, Down, Peerdown, Ready, and Running. The states listed as answers are among the possible statuses.
    </details>

22. A VGMP management group controls the switchover of all VRRP backup groups. After a VRRP backup group is added to the VGMP management group, the status of the VRRP backup group can be switched separately.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    Multiple VRRP backup groups on the same firewall are added to a VGMP management group. The VGMP management group manages the status of all VRRP backup groups in a unified manner, ensuring that the status of all VRRP backup groups in the VGMP management group is the same.
    </details>

23. The VGMP group status of the firewall is classified into two roles: master (active) and backup (backup).

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    The VGMP group status of the firewall can be Load-balance, Active, or Standby.
    </details>

24. Which of the following is not a predefined signature action?

    A. Release  
    B. Alarm  
    C. Block  
    D. Tips

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** A

    **Answer Analysis:**  
    - **Permit:** Indicates that the packets matching the signatures are allowed through and no logs are recorded.
    - **Alarm:** Indicates that the system permits the packets matching the signature but records logs.
    - **Block:** The system discards the packets matching the signature, blocks the data flow of the packets, and records logs.
    </details>

25. Which of the following is the correct process for implementing the intrusion prevention mechanism?

    A. Protocol identification -> Application data reassembly -> Feature matching -> Response processing  
    B. Reassembly of application data -> Protocol identification -> Feature matching -> Response processing  
    C. Reassembly of application data -> Feature matching -> Protocol identification -> Response processing  
    D. Feature matching -> Application data reassembly -> Protocol identification -> Response processing

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B

    **Answer Analysis:**  
    The firewall first reassembles IP fragments and TCP flows. After identifying the protocol of the packet, the firewall performs refined analysis based on the specific protocol analysis solution, extracts packet features, and matches the parsed packet features with signatures. If the packet features match the signatures, the firewall responds to the packets.
    </details>

26. Which of the following are filtering conditions of the signature filter?

    A. Category  
    B. Object  
    C. Protocol  
    D. Operating system

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABCD

    **Answer Analysis:**  
    The filtering conditions of the signature filter include the signature type, object, protocol, severity, and operating system. Only the signatures that meet all filtering conditions can be added to the signature filter.
    </details>

27. Firewall intrusion prevention analysis analyzes network traffic to detect intrusions (including buffer overflow attacks, Trojan horses, and worms), and stop intrusions in real time through certain response methods to protect enterprise information systems and network architectures from intrusion.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    Firewall intrusion prevention provides anti-worm, virus, Trojan horse, botnet, spyware, adware, CGI, cross-site scripting, injection, directory traversal, information leakage, remote file inclusion, overflow, code execution, DoS, and scanning tools, and other attack defense measures to protect network security in an all-round way.
    </details>

28. Which of the following is NOT an AAA?

    A. Certification  
    B. Authorization  
    C. Statistics  
    D. Charging  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** C

    **Answer Analysis:**  
    Authentication, Authorization, and Accounting (AAA) are short for Authentication, Authorization, and Accounting. AAA is a management mechanism for network security. It provides authentication, authorization, and accounting functions.
    </details>

29. VPN encapsulates and encrypts data. Even if hackers steal data, data cannot be cracked, ensuring data security. In addition, VPN construction does not need to change the existing network topology and does not require additional costs.

    Right  
    Wrong

<details>
<summary>Show Answer</summary>
**Correct answer:** Wrong

**Answer Analysis:**  
- While a VPN does ensure security, reliability, and manageability, it also provides greater scalability and flexibility.  
- A VPN can be utilized globally as long as Internet access is available, but the construction may incur additional costs and considerations regarding network topology.
</details>


30. If the traffic passing through the firewall matches the authentication policy, which of the following actions will be triggered?

    A. Session authentication  
    B. Pre-authentication  
    C. Authentication exemption  
    D. SSO  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABCD
    </details>

31. The system has a default authentication domain. Each user group can contain only one user and user group.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    By default, the system has a default authentication domain. Each user group can contain multiple users and user groups. Each user group can belong to only one parent user group, and each user can belong to at least one or more user groups.
    </details>

32. A user is the main body that accesses network resources. To ensure the security of network resources, proper authentication and authorization should be performed on the user.

    - Right
    - Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong
    
    **Answer Analysis:**  
    Information security incidents occur frequently. Most of them are caused by weak security awareness or misoperations of internal users and administrators. Improper permission management expands the impact scope of security incidents and deepens system damage.
    </details>

33. Which of the following is not a symmetric encryption/decryption algorithm?

    A. DES  
    B. AES  
    C. DH  
    D. SM1  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** C

    **Answer Analysis:**  
    The Diffie-Hellman (DH) asymmetric encryption and decryption algorithm is especially important in IPSec and is used to solve the key exchange problem. The same key cannot be used for a long time. To ensure sufficient security, the key needs to be obtained dynamically at both ends.
    </details>

34. Which of the following options are the characteristics of a Hash algorithm?

    A. Fast forward  
    B. Irreversible  
    C. Input sensitivity  
    D. Collision resistance  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABCD

    **Answer Analysis:**  
    - **Fast forward:** Given the plaintext and hash algorithm, the hash value is calculated in a limited time and resources.  
    - **Irreversible:** Given any hash value, it is difficult to deduce the plaintext in a finite time.  
    - **Input sensitivity:** If the input data is slightly modified, the output hash value changes significantly.  
    - **Collision resistance:** If different data is input, the output hash values cannot be the same. For a given data block, it is extremely difficult to find a data block with the same hash value.
    </details>

35. Asymmetric encryption algorithm has high efficiency, simple algorithm, low system overhead, and is suitable for encrypting a large amount of data.

    - Right  
    - Wrong  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    Asymmetric encryption algorithms are complex, take a long time to encrypt a large amount of data, and result in long encrypted packets, which is not conducive to network transmission.
    </details>

36. Which of the following information is not contained in a digital certificate?

    A. Public key of the certificate owner  
    B. Private key of the certificate owner  
    C. Identity information  
    D. Validity period of the certificate  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B

    **Answer Analysis:**  
    The private key of the owner is stored by itself and is not transmitted over the network.
    </details>

37. Which of the following are the components of a PKI system?

    A. End Entity  
    B. Certificate Authority  
    C. Certificate Registration Authority  
    D. Certificate/CRL repository  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABCD

    **Answer Analysis:**  
    The components of a PKI (Public Key Infrastructure) system include the End Entity, Certificate Authority, Certificate Registration Authority, and Certificate/CRL repository.
    </details>

38. A digital fingerprint refers to the data obtained after the sender uses its private key to encrypt the digital fingerprint.

    Right  
    Wrong  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    A digital fingerprint, also called an information digest, refers to the data obtained after the sender uses a hash algorithm to calculate the plaintext information. The sender then sends both the digital fingerprint and the plaintext to the receiver. The receiver uses the same hash algorithm to generate a fingerprint from the plaintext and compares it with the received digital fingerprint. If they match, the receiver can determine that the plaintext information has not been tampered with.
    </details>

39. Which of the following VPN technologies is a Layer 2 VPN?

    A. GRE  
    B. L2TP  
    C. IPSec  
    D. SSL  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B

    **Answer Analysis:**  
    L2TP (Layer 2 Tunneling Protocol) operates at Layer 2 of the OSI model. It provides a framework for creating a virtual private network (VPN) by encapsulating data within a tunnel at the data link layer. This is in contrast to protocols like GRE (Generic Routing Encapsulation), IPSec (Internet Protocol Security), and SSL (Secure Sockets Layer), which operate at higher layers of the OSI model.
    </details>

40. How many messages need to be exchanged during pre-shared key negotiation in aggressive mode in IKEv1 phase 1 negotiation?

    A. 2  
    B. 3  
    C. 4  
    D. 5  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B

    **Answer Analysis:**  
    In aggressive mode, three messages need to be exchanged:
    - Message 1: Exchanging SA payload, keying material, and identity information.
    - Message 2: Adding a hash authentication payload when exchanging the content of message 1.
    - Message 3: The responder's authentication of the initiator.
    </details>

41. Which of the following are SSL VPN service types?

    A. Web proxy  
    B. File sharing  
    C. Port forwarding  
    D. Network extension  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** ABCD

    **Answer Analysis:**  
    - **Web proxy:** Used when mobile users access intranet web resources.
    - **File sharing:** Utilized when mobile users access the intranet file server.
    - **Port forwarding:** Used for mobile users to access intranet TCP resources.
    - **Network extension:** Allows mobile office users to access intranet IP resources.
    </details>

42. VPN is a virtual private network, which is used to build a private and private virtual network on a public network and transmit private network traffic over the virtual network.

    Right  
    Wrong  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    A VPN (Virtual Private Network) creates a secure and encrypted connection over a public network, effectively dividing the existing physical network into logically isolated networks. It provides a secure method to transmit private network traffic without altering the network status.
    </details>

43. VPN encapsulates and encrypts data. Even if hackers steal data, data cannot be cracked, ensuring data security. In addition, VPN construction does not need to change the existing network topology and does not require additional costs.

    Right  
    Wrong  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong

    **Answer Analysis:**  
    While VPNs do provide encapsulation and encryption to secure data during transmission, they cannot guarantee that data will never be cracked if intercepted. Additionally, while VPNs offer security, reliability, and flexibility, they often require changes to network configurations and may involve additional costs for implementation and maintenance.
    </details>

44. Which of the following is not a predefined signature action?

    A. Release  
    B. Alarm  
    C. Block  
    D. Tips

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** A

    **Answer Analysis:**  
    - **Permit:** Indicates that the packets matching the signatures are allowed through and no logs are recorded.
    - **Alarm:** Indicates that the system permits the packets matching the signature but records logs.
    - **Block:** The system discards the packets matching the signature, blocks the data flow of the packets, and records logs.
    </details>

45. Which of the following is the correct process for implementing the intrusion prevention mechanism?

    A. Protocol identification -> Application data reassembly -> Feature matching -> Response processing  
    B. Reassembly of application data -> Protocol identification -> Feature matching -> Response processing  
    C. Reassembly of application data -> Feature matching -> Protocol identification -> Response processing  
    D. Feature matching -> Application data reassembly -> Protocol identification -> Response processing

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B
    
    **Answer Analysis:**  
    - The firewall first reassembles IP fragments and TCP flows.
    - After identifying the protocol of the packet, the firewall performs refined analysis based on the specific protocol analysis solution.
    - It extracts packet features and matches the parsed packet features with signatures.
    - If the packet features match the signatures, the firewall responds to the packets.
    </details>

46. Which of the following are filtering conditions of the signature filter? 

    A. Category  
    B. Object  
    C. Protocol  
    ✔ D. Operating system

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** A, B, C, D
    
    **Answer Analysis:**  
    - The filtering conditions of the signature filter include the signature type, object, protocol, severity, and operating system. 
    - Only the signatures that meet all filtering conditions can be added to the signature filter.
    </details>

47. Firewall intrusion prevention analysis analyzes network traffic to detect intrusions (including buffer overflow attacks, Trojan horses, and worms) and stops intrusions in real-time through certain response methods to protect enterprise information systems and network architectures from intrusion.

    Right  
    Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong
    
    **Answer Analysis:**  
    - Firewall intrusion prevention provides a comprehensive set of defense measures. These include anti-worm, virus, Trojan horse, botnet, spyware, adware, CGI, cross-site scripting, injection, directory traversal, information leakage, remote file inclusion, overflow, code execution, DoS, scanning tools, and other attack defense mechanisms to protect network security.
    </details>
48. Which of the following is NOT an AAA?

    A. Certification  
    B. Authorization  
    C. Statistics  
    D. Charging

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** C
    
    **Answer Analysis:**  
    - Authentication, Authorization, and Accounting (AAA) is a network security management mechanism.
    - It provides three key functions: Authentication, Authorization, and Accounting.
    </details>

49. If the traffic passing through the firewall matches the authentication policy, which of the following actions will be triggered?

    A. Session authentication  
    B. Pre-authentication  
    C. Authentication exemption  
    D. SSO

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** A, B, C, D
    
    **Answer Analysis:**  
    - **Session authentication:** When a user accesses an HTTP service, if the data flow matches the authentication policy, the firewall pushes an authentication page to request the user to perform authentication.
    - **Pre-authentication:** For non-HTTP services, users must access the authentication page for authentication; otherwise, service data flows matching the authentication policy will be blocked by the firewall.
    </details>

50. The system has a default authentication domain. Each user group can contain only one user and user group.

    Right  
    Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong
    
    **Answer Analysis:**  
    - By default, the system has a default authentication domain.  
    - Each user group can contain multiple users and user groups.  
    - Each user group can belong to only one parent user group.  
    - Each user can belong to at least one or more user groups.
    </details>

51. A user is the main body that accesses network resources. To ensure the security of network resources, proper authentication and authorization should be performed on the user.

    Right  
    Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong
    
    **Answer Analysis:**  
    - Information security incidents often result from weak security awareness or misoperations by internal users and administrators.  
    - Improper permission management can expand the scope and impact of security incidents, leading to deeper system damage.
    </details>

52. Which of the following is not a symmetric encryption/decryption algorithm?

    A. DES  
    B. AES  
    C. DH  
    D. SM1

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** C
    
    **Answer Analysis:**  
    - The Diffie-Hellman (DH) algorithm is an asymmetric encryption and decryption algorithm, crucial in IPSec for solving the key exchange problem.  
    - Since the same key cannot be used for an extended period, it is essential to obtain the key dynamically at both ends to ensure adequate security.
    </details>

53. Which of the following options are the characteristics of a Hash algorithm?

    A. Fast forward  
    B. Irreversible  
    C. Input sensitivity  
    D. Collision resistance  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** A, B, C, D
    
    **Answer Analysis:**  
    - **Fast forward:** Given the plaintext and hash algorithm, the hash value is calculated in a limited time and with limited resources.  
    - **Irreversible:** It is difficult to deduce the plaintext from any hash value in finite time.  
    - **Input sensitivity:** A slight modification to the input data results in a significant change in the output hash value.  
    - **Collision resistance:** Different inputs should produce different hash values, and it is extremely difficult to find two different data blocks that yield the same hash value.
    </details>

54. Asymmetric encryption algorithm has high efficiency, simple algorithm, low system overhead, and is suitable for encrypting a large amount of data.

    Right  
    Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong
    
    **Answer Analysis:**  
    - Asymmetric encryption algorithms are complex and take a long time to encrypt large amounts of data.  
    - Additionally, the encrypted packets tend to be lengthy, which is not conducive to efficient network transmission.
    </details>

55. Which of the following information is not contained in a digital certificate?

    A. Public key of the certificate owner  
    B. Private key of the certificate owner  
    C. Identity information  
    D. Validity period of the certificate  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B
    
    **Answer Analysis:**  
    - The private key of the certificate owner is stored securely by the owner and is not transmitted over the network.  
    - A digital certificate contains the public key, identity information, and the validity period of the certificate.
    </details>

56. Which of the following are the components of a PKI system?

    A. End Entity  
    B. Certificate Authority  
    C. Certificate Registration Authority  
    D. Certificate/CRL repository  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** A, B, C, D
    
    **Answer Analysis:**  
    - **End Entity (EE):** Also known as a PKI entity, it is the end user of PKI products or services. This can include individuals, organizations, devices (such as routers or firewalls), or processes running on a computer.  
    - **Certificate Authority (CA):** The CA serves as the trust basis of the PKI, acting as a trusted entity to issue and manage digital certificates.  
    - **Certificate Registration Authority (RA):** The RA functions as the user-facing interface for the CA, handling certificate registration and revocation applications. It verifies users' identity information and decides whether to submit applications for certificate issuance to the CA.  
    - **Certificate/CRL Repository:** This is where issued certificates and Certificate Revocation Lists (CRLs) are stored and made available for verification.
    </details>

57. A digital fingerprint refers to the data obtained after the sender uses its private key to encrypt the digital fingerprint.

    Right  
    Wrong

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** Wrong
    
    **Answer Analysis:**  
    - A digital fingerprint, also known as an information digest, is the data obtained after the sender uses a hash algorithm to calculate the plaintext information.  
    - When using the digital fingerprint, the sender transmits both the digital fingerprint and plaintext to the receiver. The receiver then applies the same hash algorithm to match the data fingerprint generated from the plaintext with the received digital fingerprint. If they match, the receiver can confirm that the plaintext information has not been tampered with.
    </details>


58. Which of the following VPN technologies is a Layer 2 VPN?

    A. GRE  
    B. L2TP  
    C. IPSec  
    D. SSL  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B
    
    **Answer Analysis:**  
    - L2TP (Layer 2 Tunneling Protocol) is a Layer 2 VPN technology that relies on the authentication provided by the Point-to-Point Protocol (PPP).  
    - Access users can be authenticated locally or through a third-party RADIUS server. Once authentication is successful, an internal IP address is allocated to the users, allowing for their authorization and management based on that IP address.
    </details>

59. How many messages need to be exchanged during pre-shared key negotiation in aggressive mode in IKEv1 phase 1 negotiation?

    A. 2  
    B. 3  
    C. 4  
    D. 5  

    <details>
    <summary>Show Answer</summary>
    **Correct answer:** B
    
    **Answer Analysis:**  
    - In aggressive mode, three messages are exchanged during the pre-shared key negotiation:  
      - **Message 1:** Exchanges SA payload, keying material, and identity information.  
      - **Message 2:** Adds a hash authentication payload when exchanging the content of Message 1.  
      - **Message 3:** Involves the responder's authentication of the initiator.
    </details>
60. VPN is a virtual private network, which is used to build a private and private virtual network on a public network and transmit private network traffic over the virtual network.

    Right  
    Wrong

<details>
<summary>Show Answer</summary>
**Correct answer:** Wrong

**Answer Analysis:**  
- A VPN creates logically isolated networks within an existing physical network to enable secure and reliable connections without altering the overall network structure.
</details>
