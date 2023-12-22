# MPLS-Layer-3-VPN
### Steps
- CE router & PE router exchange routes using dynamic routing (ospf)

- PE places the customer routes in VRF table .

- Routes in the customer's VRF table are redistributed into MB-BGP as VPNv4 routes. 

- PE routes exchange VPNv4 routes over their MP-BGP peering (PE1 & PE2).

- PE redistrubites the VPNv4 routes (OSPF----> BGP & BGP---->OSPF) .
