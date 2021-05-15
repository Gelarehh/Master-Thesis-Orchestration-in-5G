# Master-Thesis-Orchestration-in-5G

Orchestration of Routing and VNF Placement in 5G Networks


## Abstract

The fifth generation of wireless networks has been proposed as a platform to provide considerably higher network capacity, enable massive device connectivity with reduced latency and cost, and achieve considerable energy savings. In this regard, network design, management, and upgrades require innovative technologies and architectures. Enterprise and service provider networks are increasingly making use of Virtualized Network Functions (VNFs) and Software-Defined Networking (SDN) to reap the benefits of reduced CAPital EXpenditures (CAPEX) and OPerating EXpenses (OPEX).

In this research, the problem of placing virtual network functions on existing resources and data routing through these functions to execute a particular service chain is investigated. A network consisting of switches, servers, and links with determined specifications was designed and simulated to this end. On the next step, an optimization problem was proposed, which was subjected to minimizing the total cost of utilizing links and severs of the network. The service provider view and the cloud provider requirements were both taken into account while modeling the cost function. Besides network constraints and topology constraints, a QoS constraint was considered, which exerted an upper bound on the congestions of the links. Due to the NP-hard nature of the problem, a small-scale network was simulated using MOSEK in MATLAB, and optimal results to MILP were driven. In the following, two heuristic algorithms were presented to solve the NP-hard optimization problem, and the performance of one of them was evaluated and compared to optimal results.

**keywords**: 5G, Software-Defined Networking, Network Function Virtualization, Routing, Heuristic
