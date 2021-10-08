

- Books
    - [The Mythical Man-Month](http://www.cesarkallas.net/arquivos/livros/informatica/Addison.Wesley.The.Mythical.Man-Month.Essays.on.Software.Engineering.20th.Anniversary.Edition.pdf) - Frederick P. Brooks, Jr
    - [No Silver Bullet](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf)

------------------------------------------------------------

- [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)
    - [Shortest path problem](https://en.wikipedia.org/wiki/Shortest_path_problem)
        - [Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
    - [Minimum spanning tree](https://en.wikipedia.org/wiki/Minimum_spanning_tree)

------------------------------------------------------------

- Alogrithm
    - [COMP 271 Design and Analysis of Algorithms](https://home.cse.ust.hk/~dekai/271/)
    - Dijkstra
        - [Lecture 10: Dijkstra’s Shortest Path Algorithm](https://home.cse.ust.hk/~dekai/271/notes/L10/L10.pdf)
        - [Understanding Dijkstra Algorithm](https://www.researchgate.net/publication/273264449_Understanding_Dijkstra_Algorithm)
        - [Lecture 18 Solving Shortest Path Problem: Dijkstra’s Algorithm](http://www.ifp.illinois.edu/~angelia/ge330fall09_dijkstra_l18.pdf)
        - [DIJKSTRA'S ALGORITHM](https://www.cartagena99.com/recursos/alumnos/apuntes/dijkstra_algorithm.pdf)

------------------------------------------------------------

- Consensus
    - Proof of work
        - [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)
    - [Proof of authority](https://en.wikipedia.org/wiki/Proof_of_authority)
    - [Proof of space](https://en.wikipedia.org/wiki/Proof_of_space)
        - Concepts
            - Proof of storage
            - Proof of capacity
            - Proof of space-time
        - Uses
            - Signum (Burstcoin)
                - [Bussiness White Paper](https://signum.network/wp/Signum_Business_Whitepaper.pdf)
                - Poc+
                    - PoC+ Capacity
                    - PoC+ Commitment
                    - PoC+ Factor
            - Siacoin
                - [Simple Proofs of Space-Time and Rational Proofs of Storage](https://eprint.iacr.org/2016/035)
            - SpaceMint
                - [SpaceMint: A Cryptocurrency Based on Proofs of Space](https://eprint.iacr.org/2015/528.pdf)
            - chia
                - [Bussiness Whitepaper](https://www.chia.net/assets/Chia-Business-Whitepaper-2021-02-09-v1.0.pdf)
            - Spacemesh
                - [Sia: Simple Decentralized Storage](https://sia.tech/sia.pdf)
    - [Proof of History](https://tokens-economy.gitbook.io/consensus/chain-based-proof-of-capacity-space/proof-of-history)
        - [Proof of History: A Clock for Blockchain](https://medium.com/solana-labs/proof-of-history-a-clock-for-blockchain-cf47a61a9274)
    - BFT
        - [Tower BFT](https://medium.com/solana-labs/tower-bft-solanas-high-performance-implementation-of-pbft-464725911e79)
    - Proof of Replication
        - [PoReps: Proofs of Space on Useful Data](https://eprint.iacr.org/2018/678.pdf)
    - [Proof of data possession](http://cryptowiki.net/index.php?title=Proof_of_data_possession)
        - [Provable Data Possession at Untrusted Stores](https://people.eecs.berkeley.edu/~dawnsong/papers/p598-ateniese)
        - [A Blockchain and Directed Acyclic Graph-integrated Secure Data Flow System](https://cybervein.obs.cn-east-3.myhuaweicloud.com/Whitepaper_V3_CyberVein%20English.pdf)

        
------------------------------------------------------------

- [SCALING OVERVIEW](https://ethereum.org/en/developers/docs/scaling/)
    - ON-CHAIN SCALING
        - [Sharding](https://ethereum.org/en/eth2/shard-chains/)
    - OFF-CHAIN SCALING
        - Layer 2 Scaling
            - Zero Knowledge rollups
                - [Loopring](https://loopring.org/#/)
                    - [Loopring: A Decentralized Token Exchange Protocol](https://loopring.org/resources/en_whitepaper.pdf)
                    - [Design Doc](https://github.com/Loopring/protocols/blob/master/packages/loopring_v3/DESIGN.md)
                - [Starkware](https://starkware.co/)
                - [Matter Labs zkSync](https://zksync.io/)
                    - [zkPorter: a breakthrough in L2 scaling](https://medium.com/matter-labs/zkporter-a-breakthrough-in-l2-scaling-ed5e48842fbf)
                - [Aztec 2.0](https://aztec.network/)
                    - [PlonK: Permutations over Lagrange-bases for Oecumenical Noninteractive arguments of Knowledge](https://eprint.iacr.org/2019/953.pdf)
                - [Hermez network](https://hermez.io/)
                    - [Hermez White Paper](https://hermez.io/hermez-whitepaper.pdf)
                - [dYdX](https://dydx.exchange/)
                    - [Starkware's documentation](https://docs.starkware.co/starkex-docs-v2-deprecated/)

            - Optimistic rollups
                - Arbitrum
                    - [Arbitrum Rollup Basics](https://developer.offchainlabs.com/docs/rollup_basics)
                - [Optimistic](https://optimism.io/)

            - State channels
                - [Lightning Network](https://lightning.network/?ref=block123)
                    - [The Bitcoin Lightning Network](https://lightning.network/lightning-network-summary.pdf)
                    - [The Bitcoin Lightning Network:: Scalable Off-Chain Instant Payments](https://lightning.network/lightning-network-paper.pdf)
                - [Raiden Network](https://raiden.network/?ref=block123)
                    - [Raiden Network Protocol Explained](https://www.youtube.com/watch?v=jlcYmQHHutU&t=591s)
                        - PAYMENT CHANNELS
                        - MEDIATED TRANSFERS
                        - ROUTING A PAYMENT
                        - SEND MULTIPLENDING TRANSFERS
                        - SETTLE MULTIPLENDING TRANSFERS
                    - [Mediation Fees](https://raiden-network.readthedocs.io/en/stable/using-raiden-on-mainnet/overview.html#open-a-channel)
                        - [Dynamic Mediation Fees in Raiden Explained](https://medium.com/raiden-network/dynamic-mediation-fees-in-raiden-explained-dbc29f032e4b)
                        - [Mediation Fees calculation and message format](https://github.com/raiden-network/raiden-services/blob/master/adr/003-mediation-fees.md)
                        - [Risk of draining funds through imbalance fees](https://docs.raiden.network/en/v2.0.0/adr/0007-drain-imbalance-fee.html)
                - [xLumi](https://v.systems/payment)
                    - [xLumi: Payment Channel Protocol and Off-chain 2 Payment in Blockchain Contract Systems](https://v.systems/static/xlumiwhitepaperen.pdf)
                - [L4](https://l4.ventures/)
                    - [State channels](https://statechannels.org/?ref=block123)
                    - [Making Sense of Ethereum’s Layer 2 Scaling Solutions: State Channels, Plasma, and Truebit](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4)
                        
            - Reference
                - [Layer 2 Blockchain Scaling: a Survey](https://arxiv.org/pdf/2107.10881.pdf)
                - [What Are Cryptocurrency Layer 2 Scaling Solutions?](https://coinmarketcap.com/alexandria/article/what-are-cryptocurrency-layer-2-scaling-solutions)
                    - Zero-Knowledge Rollups 
                    - Optimistic Rollups
                    
                - [List of Awesome Layer 2 Projects](https://www.block123.com/en/feature/awesome-layer-2-list/)
        - [Sidechains](https://ethereum.org/en/developers/docs/scaling/sidechains/)
        - Plasma
            - [Plasma: Scalable Autonomous Smart Contracts](https://plasma.io/plasma.pdf)

