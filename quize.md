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

