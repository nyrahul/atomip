# AtomIP
Constrained IP based middleware for IoT networks

Requirements:
1. Support light weight stack suitable for constrained devices ... keep it light weight but practical i.e. do not compromise security for light weight
2. Support different compression techniques at network, transport and application layers for IoT scenarios (support 6LoWPAN compression, lpwan SCHC, ROHC, IPComp)
3. Support compressed signalling procedures such as (Optimized ND6 RFC6775)
4. Support specific neighbor cache table mgmt procedure which allows constrained implementations.
5. Support for multicast protocols for constrained networks (such as MPL)

The aim is not to produce a ultra thin middleware and compare on size front. But to provide a middleware which has certain features which are more practical for constrained nodes.
