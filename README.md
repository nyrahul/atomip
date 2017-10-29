# AtomIP
Constrained IP based middleware for IoT networks

Requirements:
1. Support light weight stack suitable for constrained devices ... keep it light weight but practical i.e. do not compromise security for light weight. Follow secure coding guidelines and produce a stack which can be torture-tested.
2. Support different compression techniques at network, transport and application layers for IoT scenarios (support 6LoWPAN compression, lpwan SCHC, ROHC, GHC)
3. Support compressed signalling procedures such as (Optimized ND6 RFC6775)
4. Support specific neighbor cache table mgmt procedure which allows constrained implementations.
5. Support for multicast protocols for constrained networks (such as MPL)
6. Support for configuration mgmt and topology mgmt using COMI/NETCONF/RESTCONF/SIDs.
7. Support generic header compression (GHC)
8. Supoort data structure design which reduces memory footprint (It may increase runtime processing). One example is routing table, neighbor table should map to 6lo context id table for mapping prefix information, thus reducing network prefix storage cost per entry.
9. Support RPL-based routing protocol with all the protocol flexibility (multi-instance, local/global dodags, p2p-rpl, storing/non-storing etc)

The aim is not to produce a ultra thin middleware and compare on size front. But to provide a secure middleware which has certain features which are more practical for constrained nodes.
