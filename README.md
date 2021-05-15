The Proton Network is an off-chain scaling solution, enabling near-instant, low-fee and scalable payments. It's complementary to the Meshcoin Blockchain and works with any MRC20 compatible token. The Proton project is work in progress. Its goal is to research state channel technology, define protocols and develop reference implementations.

The Proton Network is an infrastructure layer on top of the Meshcoin Blockchain. While the basic idea is simple, the underlying protocol is quite complex and the implementation non-trivial. Nonetheless the technicalities can be abstracted away, such that developers can interface with a rather simple API to build scalable decentralized applications based on the Proton Network.
 
### Transaction channel
When a user gets connected to a relay node via DAPP, they need to pay network fees to the relay node. As both parties may involve in illegal acts, the Pronto channel is developed to provide a fast and safe transaction mechanism free of charge to ensure transaction fairness. All the user needs to do is to create an on-chain channel when using the relay node network for the first time. When using the network, he or she needs to submit a Hash proof to the relay node via Pronto at a fixed interval and pay the network fees. The relay node can withdraw the fees from the on-chain channel any time via Hash proofs, and prove the relay workload.

### Channel group
Subject to network service uncertainties, a single service provider can hardly guarantee service reliability, and a Layer 2 distributed network is then built. Several relay nodes can form a group based on geographic locations and user preferences, providing the users with network services. The user needs to create an on-chain channel for the group. A distributed consensus is reached among Layer2 networks of relay nodes based on the RAFT protocol. When a single point of failure occurs, DAPP will connect the user to other nodes in service, thus enhancing the service reliability and improving the user experience.

### More
Pronto Network is more than a network fee payment channel. The fast and safe transaction mechanism free of charge creates more application scenarios for DAPP in the Meshcoin.
