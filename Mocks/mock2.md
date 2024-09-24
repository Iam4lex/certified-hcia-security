## Final exam in the portal.

1. When firewalls are deployed in hot standby mode, which of the following protocols is used to switch the status of the entire VRRP group?

    A. VRRP  
    B. VGMP  
    C. ICMP  
    D. IGMP  

  <details>
  <summary>Show Answer</summary>
  **Correct answer:** B. VGMP 
  </details>

2. Which of the following statements is correct about the function of lateral movement in network penetration?

    A. An attacker obtains the IP address, domain name, active port, and communication information of the target network through scanning and network monitoring to lay a foundation for subsequent attacks.  
    B. After accessing the target system, the attacker cannot perform lateral movement due to a lack of privileges. Therefore, the attacker may try to elevate privileges.  
    C. Lateral movement is to penetrate other devices that may have vulnerabilities on the network through controlled hosts or servers.  
    D. Communicate with the customer to understand the target of the penetration test, such as the system, server, and IP address.  

  <details>
  <summary>Show Answer</summary>
  **Correct answer:** C. Lateral movement is to penetrate other devices that may have vulnerabilities on the network through controlled hosts or servers.
  </details>

3. Which of the following is a private IP address?

    A. 192.200.1.1  
    B. 172.32.1.1  
    C. 192.1.1.1  
    D. 172.20.2.1  

<details>
<summary>Show Answer</summary>
**Correct answer:** D. 172.20.2.1
</details>

4. Which of the following statements is correct about the characteristics of a DDoS attack?

    A. An attacker intrudes into the target system through a backdoor program.  
    B. The purpose of such an attack is to steal confidential information from the target system.  
    C. The attack behavior can prevent the target system from processing the requests of authorized users.  
    D. If the target system has no vulnerability, the remote attack cannot succeed.  

<details>
<summary>Show Answer</summary>
**Correct answer:** C. The attack behavior can prevent the target system from processing the requests of authorized users.
</details>

5. Network penetration simulates hackers' intrusion behaviors and thought patterns to perform non-destructive security tests on customer systems. Which of the following is the correct sequence of the network penetration process?

    A. Confirm the target -> Collect information -> Implement penetration -> Perform lateral movement -> Elevate privileges -> Clear traces  
    B. Collect information -> Confirm the target -> Implement penetration -> Perform lateral movement -> Elevate privileges -> Clear traces  
    C. Confirm the target -> Collect information -> Perform lateral movement -> Implement penetration -> Elevate privileges -> Clear traces  
    D. Confirm the target -> Collect information -> Implement penetration -> Perform lateral movement -> Clear traces -> Elevate privileges  

<details>
<summary>Show Answer</summary>
**Correct answer:** A. Confirm the target -> Collect information -> Implement penetration -> Perform lateral movement -> Elevate privileges -> Clear traces
</details>

6. Which of the following statements is incorrect about TTL in IP packets?

    A. TTL is the maximum number of hops that an IP packet can be forwarded on a computer network.  
    B. The main function of TTL is to prevent IP packets from being circulated over a network infinitely, thereby saving network resources.  
    C. The TTL value decrements by 1 every time a packet is forwarded to a Layer 3 node.  
    D. The TTL value of a packet ranges from 0 to 4095.  

<details>
<summary>Show Answer</summary>
**Correct answer:** D. The TTL value of a packet ranges from 0 to 4095.
</details>

7. In tunnel mode of IPsec, to authenticate a new IP header, which of the following IPsec protocols needs to be used?

    A. MD5  
    B. SHA1  
    C. ESP  
    D. AH  

<details>
<summary>Show Answer</summary>
**Correct answer:** D. AH
</details>

8. Which of the following attacks is not a network-layer attack?

    A. Smurf attack  
    B. IP sweep  
    C. IP spoofing attack  
    D. Port scanning  

<details>
<summary>Show Answer</summary>
**Correct answer:** D. Port scanning
</details>

9. Which of the following statements is correct about a firewall's interzone security policies?

    A. Interzone security policies are matched sequentially from the one with the smallest ID.  
    B. Interzone security policies are matched sequentially from the top down.  
    C. Interzone security policies are matched sequentially from the one with the largest ID.  
    D. Interzone security policies are automatically sorted by ID. If the position of a policy changes, the ID of the policy changes accordingly.  

<details>
<summary>Show Answer</summary>
**Correct answer:** B. Interzone security policies are matched sequentially from the top down.
</details>

10. Which of the following statements is incorrect about the RADIUS protocol?

    A. By default, UDP is used, and the authentication and authorization port numbers are 1812 and 1813 or 1645 and 1646, respectively.  
    B. It encrypts only the password field in an authentication packet.  
    C. Authentication and authorization are processed together.  
    D. It supports authorization of configuration commands.  

<details>
<summary>Show Answer</summary>
**Correct answer:** D. It supports authorization of configuration commands.
</details>

11. Huawei Redundancy Protocol (HRP) is used to synchronize data such as the key configurations and connection status of the active firewall to the standby firewall. Which of the following data is beyond the synchronization scope?

    A. Routing table  
    B. Security policies  
    C. Blacklist  
    D. NAT policies  

<details>
<summary>Show Answer</summary>
**Correct answer:** A. Routing table
</details>

12. Which of the following messages can provide error information and IP packet processing information for source ends?

    A. IGMP  
    B. TCP  
    C. UDP  
    D. ICMP  

<details>
<summary>Show Answer</summary>
**Correct answer:** D. ICMP
</details>

13. If packet loss occurs when hosts A and B communicate with each other through TCP, how does TCP ensure reliability?

    A. Host B sends ICMP packets to host A to notify data loss.  
    B. The sliding window mechanism is used between the two hosts to ensure reliability.  
    C. Host B uses the ACK field to instruct host A to retransmit packets.  
    D. The Option field in TCP packets is used to ensure reliability of host A and host B.  

<details>
<summary>Show Answer</summary>
**Correct answer:** C. Host B uses the ACK field to instruct host A to retransmit packets.
</details>

14. Which one of the following parts is not included in a digital certificate?

    A. Name of the certificate holder  
    B. Certificate validity period  
    C. Certificate private key  
    D. Certificate public key  

<details>
<summary>Show Answer</summary>
**Correct answer:** C. Certificate private key
</details>

15. When an administrator wants to configure a USG series firewall through the console port, which of the following configurations should be made in Putty?

    A. 4800 bps, 8 data bits, 1 stop bit odd parity check, and no flow control  
    B. 9600 bps, 8 data bits, 1 stop bit, even parity check, and hardware-based flow control  
    C. 9600 bps, 8 data bits, 1 stop bit, no parity check, and no flow control  
    D. 19200 bps, 8 data bits, 1 stop bit, no parity check, and no flow control  

<details>
<summary>Show Answer</summary>
**Correct answer:** C. 9600 bps, 8 data bits, 1 stop bit, no parity check, and no flow control
</details>

16. On a USG firewall, which of the following commands is used to view current session entries?

    A. display firewall statistic  
    B. display firewall routing table  
    C. display firewall session table  
    D. display firewall fib session  

<details>
<summary>Show Answer</summary>
**Correct answer:** C. display firewall session table
</details>

17. Which of the following values is the default security level of the Trust zone on a Huawei USG firewall?

    A. 5  
    B. 50  
    C. 85  
    D. 100  

<details>
<summary>Show Answer</summary>
**Correct answer:** C. 85
</details>


