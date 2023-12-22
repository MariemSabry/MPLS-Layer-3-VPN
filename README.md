# MPLS-Layer-3-VPN
MPLS Layer 3 VPNs provide peer-to-peer connectivity between private customer sites 
across a shared network. 


The MPLS domain is referred to as the P-network, and the customer sites are referred 
to as the C-network.


This section explores how you can use MPLS Layer 3 VPNs to connect your private 
networks over your provider’s public network.
### Steps
- CE router & PE router exchange routes using dynamic routing (ospf)

- PE places the customer routes in VRF table .

- Routes in the customer's VRF table are redistributed into MB-BGP as VPNv4 routes. 

- PE routes exchange VPNv4 routes over their MP-BGP peering (PE1 & PE2).

- PE redistrubites the VPNv4 routes (OSPF----> BGP & BGP---->OSPF) .


"This Project in EVE from scratch"
