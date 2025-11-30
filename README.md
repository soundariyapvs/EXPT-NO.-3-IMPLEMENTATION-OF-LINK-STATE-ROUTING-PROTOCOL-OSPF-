# EXPT NO.3 IMPLEMENTATION OF LINK STATE ROUTING PROTOCOL OSPF
# AIM

To connect computers in multiple networks using Open Shortest Path First Routing Protocol and to verify the connectivity between computers.

# EQUIPMENTS REQUIRED
PC With Cisco Packet Tracer 5.0 Software

# IP ASSIGNMENT
| NAME     | IP ADDRESS      | SUBNET MASK     | NETWORK       | CLASS | GATEWAY         |
|----------|------------------|------------------|---------------|-------|------------------|
| PC0      | 192.168.0.1      | 255.255.255.0    | 192.168.0.0   | C     | 192.168.0.200    |
| PC1      | 192.168.0.2      | 255.255.255.0    | 192.168.0.0   | C     | 192.168.0.200    |
| PC2      | 192.168.1.1      | 255.255.255.0    | 192.168.1.0   | C     | 192.168.1.200    |
| PC3      | 192.168.1.2      | 255.255.255.0    | 192.168.1.0   | C     | 192.168.1.200    |
| PC4      | 192.168.2.1      | 255.255.255.0    | 192.168.2.0   | C     | 192.168.2.200    |
| PC5      | 192.168.2.2      | 255.255.255.0    | 192.168.2.0   | C     | 192.168.2.200    |
| ROUTER0  | 192.168.0.200    | 255.255.255.0    | 192.168.0.0   | C     | -                |
| ROUTER0  | 192.168.1.200    | 255.255.255.0    | 192.168.1.0   | C     | -                |
| ROUTER1  | 192.168.1.201    | 255.255.255.0    | 192.168.1.0   | C     | -                |
| ROUTER1  | 192.168.2.200    | 255.255.255.0    | 192.168.2.0   | C     | -                |


# NETWORK DIAGRAM
<img width="1654" height="1015" alt="image" src="https://github.com/user-attachments/assets/265a80d5-6426-42b3-87c8-84e7f1013de0" />


# PROCEDURE
```
STEP 1: Open a Packet Tracer Software.
STEP 2: Drag two 2900 Switches, two Cisco 1800 Routers, four PC Terminals from tool bar and drop it in work area.
STEP 3: Connect all the PC Terminals and Routers through Switches as shown in the network diagram using CAT 6 Patch cables.
STEP 4: Configure IP address and Gateway in all PC Terminals.
STEP 5: Configure Delhi router IP address, save configuration and restart Delhi router. STEP 6: Configure Chennai router IP address, save configuration and restart Chennai router. STEP 7: Check the connectivity between the computers in network.
STEP 8: Configure OSPF in Delhi router, Save configuration and restart Delhi router.
STEP 9: Configure OSPF in Chennai router, Save configuration and restart Chennai router.
STEP 10: Verify the connectivity between PC Terminals in different networks using Ping command.
STEP 11: Check the routing table in Delhi router and Chennai router using show ip route command
```
# OUTPUT
<img width="1611" height="992" alt="image" src="https://github.com/user-attachments/assets/3a903c70-e47d-4158-a236-4b9ee6ccb643" />

<img width="1674" height="1007" alt="image" src="https://github.com/user-attachments/assets/26cf6805-0f84-4879-814e-d6731974d956" />



# RESULT
Thus the computers in multiple networks using Open Shortest Path First Routing Protocol is connected and the connectivity between the computers is verified.

