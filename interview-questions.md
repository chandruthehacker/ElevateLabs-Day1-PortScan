## 🧠 Interview Q&A

1. **What is an open port?**  
   A network port that is actively accepting connections. Indicates a service is running.

2. **How does Nmap perform a TCP SYN scan?**  
   It sends SYN packets to target ports and waits for SYN-ACK responses. If SYN-ACK is received, the port is open. This is known as a "half-open scan" because the connection is never completed.

3. **What are the risks of open ports?**  
   Attackers can exploit services running on open ports. For example, SMB (port 445) was targeted by the WannaCry ransomware.

4. **What is the difference between TCP and UDP scans?**  
   - **TCP scan**: Establishes a connection or partial connection; more reliable and detectable.  
   - **UDP scan**: Connectionless; harder to detect but slower and less reliable due to lack of responses.

5. **How can open ports be secured?**  
   - Use firewalls to restrict access.  
   - Disable unused services.  
   - Apply security patches regularly.  
   - Use techniques like port-knocking for stealth.

6. **What is the firewall’s role?**  
   A firewall controls incoming and outgoing traffic, blocks unwanted connections, and limits which services are exposed to a network.

7. **Why do attackers scan ports?**  
   To identify active services, detect vulnerabilities, and map out a network before launching an attack.

8. **What is Wireshark’s role in port scanning?**  
   It captures and visualizes network traffic, allowing analysis of how Nmap scans work (e.g., SYN packets and responses). It helps verify scan behavior and network reactions.
