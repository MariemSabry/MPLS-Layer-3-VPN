# MPLS-Layer-3-VPN
### steps
1- CE router & PE router exchange routes using dynamic routing (ospf)
2- PE places the customer routes in VRF table .
3- Routes in the customer's VRF table are redistributed into MB-BGP as VPNv4 routes. 
4- PE routes exchange VPNv4 routes over their MP-BGP peering (PE1 & PE2).
5- PE redistrubites the VPNv4 routes (OSPF----> BGP & BGP---->OSPF) .
