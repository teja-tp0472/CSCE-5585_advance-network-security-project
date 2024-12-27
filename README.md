
# Desining and implementing a secure network 

This project focuses on designing and implementing a secure network infrastructure resistant to internal and external cyber threats. It leverages advanced network security tools and best practices to monitor, detect, and mitigate malicious activities and unauthorized access.
## Objective

1. Develop a secure and resilient network.

2. Segment and regulate traffic across VLANs.

3. Implement robust monitoring and prevention mechanisms using tools like Sophos Firewall, GNS3, and Wireshark.

## Tools and Technologies

1. Sophos Firewall: Unified tool for traffic management, access controls, and intrusion prevention.

2. GNS3: Network emulator for designing and testing network scenarios.

3. VMware: Virtualization platform for creating test environments.

4. Wireshark: Tool for packet analysis and network traffic monitoring.

5. Netcat: Utility for connectivity probing and penetration testing.

6. Nmap: Used for network scanning and vulnerability assessment.

## Network Topology

1. Pentest Machine : Acts as a external attacker to the internal network through the firewall.

2. Cloud : This ia representing a external environment connection where a remote access can be given to a employee.

   Using this cloud we are testing the inbound and the outbound traffic through the firewall.

3. VPN User : Remote accesing employee, to the internal network throgh SSL VPN connection.

4. Sophos Firewall : Used for traffic filtering and also giving limited access to any authorized user, to provide a secure remote access. IPS and IDS can be implemented on malicious traffic. This is acting as a central security device in the network.

5. Internal Network : HR-VLAN, Management-VLAN, DMZ. Where HR-VLAN is connected to the Port A of the firewall, Management-VLAN to the port B of the firewall, Port C of the firewall is connected to the DMZ(Demilitarized Zone). DMZ has onlt http or https services. In this project DMZ acts as a buffer zone between internal and external network.
## Security Enhancement

Intrusion Prevention System (IPS): Monitored and blocked malicious activities using predefined and custom rules
## Results

1. Enhanced network security with effective risk mitigation strategies.

2. Documented baseline configurations and recommended regular audits for compliance.

3. Demonstrated layered security measures for robust protection.
## How to run

1. Clone this repository.

2. Use GNS3 to emulate the provided network topology.

3. Import and configure Sophos Firewall using the OVA image in VMware.

4. Test and validate network configurations using the provided testing tools.
## Contribution

Feel free to fork this repository and submit pull requests for improvements. For major changes, please open an issue first to discuss the proposed changes.
