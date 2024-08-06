# Basic Networking Project using Cisco Packet Tracer

## Project Overview
This project involves creating and configuring a network with two subnets using Cisco Packet Tracer. The network is based on the base network address 192.168.40.0, with subnetting performed to accommodate two departments.

## Project Objectives
- To divide the base network 192.168.40.0 into two subnets.
- To configure network devices in Cisco Packet Tracer to reflect the subnetting.

## Subnetting Details

- **Base Network Address**: 192.168.40.0
- **Number of Subnets**: 2

**Calculation of Subnets:**
- \( 2^n = 2 \) (where \( n \) is the number of bits to change)
- \( n = 1 \) (1 bit changed)

**Subnet Mask:**
- Original Subnet Mask: 255.255.255.0
- Since one bit must be changed: 11111111.11111111.11111111.10000000
- **Subnet Mask**: 255.255.255.128

**Slash Notation**: /25 (8 + 8 + 8 + 1 = 25)

## Subnet Details

**1st Subnet:**
- **Subnet Mask**: 255.255.255.128
- **Network ID**: 192.168.40.0
- **Range of Valid Hosts**: 192.168.40.1 – 192.168.40.126
- **Broadcast ID**: 192.168.40.127

**2nd Subnet:**
- **Subnet Mask**: 255.255.255.128
- **Network ID**: 192.168.40.128
- **Range of Valid Hosts**: 192.168.40.129 – 192.168.40.254
- **Broadcast ID**: 192.168.40.255

## Implementation Steps

1. **Set Up the Network in Cisco Packet Tracer**:
   - Create the network topology with routers, switches, and end devices.
   - Configure the IP addresses for devices in the two subnets.

2. **Configure Devices**:
   - Assign IP addresses and subnet masks to each device.
   - Configure routing to ensure connectivity between the subnets.
   - ![image](https://github.com/user-attachments/assets/7e2c5235-97b7-43a0-8c08-794f11ff0588)


3. **Testing**:
   - Use ping and other network testing tools to verify connectivity within and between the subnets.
   - ![image](https://github.com/user-attachments/assets/1eb0c199-18bc-4c26-846a-192e6ab5590b)


## Results and Analysis
- Both subnets are correctly configured and devices can communicate within their respective subnets and across subnets.
- The configuration meets the project objectives of dividing the network for two departments with proper subnetting.

## Conclusion
The project successfully demonstrates the creation of two subnets from a base network address and configuring devices in Cisco Packet Tracer to reflect the subnetting.

## Future Improvements
- Explore additional subnetting for more departments.
- Implement VLANs to further segment the network within each subnet.
