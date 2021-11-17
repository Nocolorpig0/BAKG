# BAKG
Experimental data of BAKG.

The experimental data involved in the paper is stored here, including the read/write latency of the blockchain and the computational latency of the keys.

We choose the FISCO-BCOS consortium blockchain as the simulation platform which adopts PBFT as the consensus protocol. Different numbers of blockchain nodes are hosted on Ubuntu 16.04 Virtual Machine which has 1 core, 8G memory and 1.5GHz CPU. The network connection of each node is configured in bridge mode to directly connect with the physical network, which is kept in the same local network of the host.We design three simulation scenarios. All three scenarios have 10ms latency and 0.1% packet loss rate which refers to a good network environment. Scenario 1 has 5 blockchain nodes, scenario 2 has 18 blockchain nodes and scenario 3 has 30 blockchain nodes. Each simulation is conducted with 100 experiments, and the final result takes the average of the tested delay.

There are three lengths of key factors in our prototype system, 112 bits, 160 bits and 256 bits. We test the latency of key generation and combination in the same configured environment. Each set of tests was performed 50 times and the average was taken as the final result.
