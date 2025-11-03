# AWS project 1 - Building a custom VPC from scracth
## Overview
In this project i created a **custom virtual private cloud(VPC)** in AWS to understand how networking works in cloud.
## Architecture diagram ##

<pre>
              
                               +----------------+
                               |     Internet   |
                               +-------+--------+
                                       |
                               [Intrnet gateaway]
                                       |
                               +----------------+
                               |  Public subnet |
                               |  (10.0.0.0/24) |                           
                               +--------+-------+
                                        |
                               [VPC: 10.0.0.0/16]
</pre>
*Note: This diagram show data flow not creation order*

## Steps to Create the VPC ##

1. **Set up a VPC**. To set up a VPC i had to **define IPv4 CIDR block**.
2. **Created a Subnet** and selected availablity zone and then enabled auto assign ip settings.
3. **Created an internet gateway** and attached to VPC.

## Screenshots ##
<img width="3420" height="2196" alt="Image 10-27-25 at 6 09 AM" src="https://github.com/user-attachments/assets/e685bc66-505b-40f7-b527-610c0c0e99f0" />
<img width="2930" height="1430" alt="Image 11-3-25 at 12 44 AM" src="https://github.com/user-attachments/assets/5acb229d-cbd2-4bea-909c-0f2132e80aa2" />
<img width="2930" height="656" alt="Image 11-3-25 at 12 45 AM" src="https://github.com/user-attachments/assets/0d06a91b-5be1-466b-bc4a-1e660307c546" />
<img width="1404" height="1364" alt="Image 11-3-25 at 3 05 AM" src="https://github.com/user-attachments/assets/5a36f7e1-050a-4c44-970f-e7f9afeab016" />

## Key learnings ##
- Understood AWS networking fundamentals like VPC,CIDR,Subnets,intenet gateway
- Created a custom VPC from scratch

## Next steps ##
In the next project i will extend this setup and build VPC Traffic flow and Security.

## CREDITS/TOOLS ##
**Repository by:** Akhil Thalari

**Tools used:** AWS management console

