[![](https://www.discotec.org/2021/discotec2021-banner.jpeg)](https://www.discotec.org/2021/)

## FOCODILE 2021 - 2nd International Workshop on Foundations of Consensus and Distributed Ledgers

FOCODILE 2021 is one of the workshops at [DisCoTec 2021](https://www.discotec.org/2021/), the 16th International Federated Conference on Distributed Computing Techniques. It will be held on June 18, 2021. 

COVID-19 update: in case of a physical event, remote participation will be possible. Please check the DisCoTec 2021 main page for more details.

## Scope
FOCODILE is a forum to exchange ideas and recent research findings on theoretical foundations of consensus and blockchain technology. Topics include, but are not limited to:

* Formal models of distributed consensus
* Blockchain-specific cryptographic primitives and protocols
* Formal verification of blockchain protocols and smart contracts
* Byzantine fault tolerance and consensus
* Design and analysis of distributed ledgers
* Blockchain consensus mechanisms
* Privacy and anonymity in cryptocurrencies
* Game-theoretic approaches to blockchains
* Post-quantum blockchain protocols
* Performance and scalability of blockchain systems


## Keynote Speaker

## Lewis Tseng: High-performance crash-tolerant SMR in a single datacenter 

[Boston University](lewis.tseng@bc.edu)
<br/><br/>
State-Machine Replication (SMR) uses replication to ensure that a service is available and consistent in the presence of failures. 
One popular mechanism for implementing SMR is to use a consensus algorithm to agree on the total order of client requests, namely, a log-based SMR approach. 
I will present our recent works on improving log-based SMR deployed in a single datacenter:
* in the first work, we use randomization to simplify the design. Compared to Multi-Paxos and EPaxos, our system maintains high performance with reduced engineering complexity, by exploiting the stable network infrastructure in a single datacenter.
* in the second work, we port Paxos to our new model which exploits the power of remote direct memory access (RDMA). 
Our system offers good performance while demonstrating better tail latency and faster fail-over compared to a state-of-the-art competitor.
<br/><br/>
 
## Titles

### Dynamical Analysis of the EIP-1559 Ethereum Fee Market  
Stefanos Leonardos, Singapore University of Technology and Design
<br/><br/>
Participation in permissionless blockchains results in competition over system resources, which needs to be controlled with fees. 
Ethereum's current fee mechanism is implemented via a first-price auction that results in unpredictable fees as well as other inefficiencies. 
EIP-1559 is a recent, improved proposal that introduces a number of innovative features such as a dynamically adaptive base fee that is burned, instead of being paid to the miners. 
Despite intense interest in understanding its properties, several basic questions such as whether and under what conditions does this protocol self-stabilize have remained elusive thus far.
We perform a thorough analysis of the resulting fee market dynamic mechanism via a combination of tools from game theory and dynamical systems. 
We start by providing bounds on the step-size of the base fee update rule that suffice for global convergence to equilibrium via Lyapunov arguments. 
In the negative direction, we show that for larger step-sizes instability and even formally chaotic behaviour are possible under a wide range of settings. 
We complement these qualitative results with quantitative bounds on the resulting range of base fees. 
We conclude our analysis with a thorough experimental case study that corroborates our theoretical findings.
<br/><br/>

 
### Recursive Virtual Payment Channels for Bitcoin
Orfeas Stefanos Thyfronitis Litos, University of Edinburgh
<br/><br/>
A dominant approach towards the solution of the scalability problem in blockchain systems has been the development of layer 2 protocols and specifically payment channel networks (PCNs) such as the Lightning Network (LN) over Bitcoin. 
Routing payments over LN requires the coordination of all path intermediaries in a multi-hop round trip that encumbers the layer 2 solution both in terms of responsiveness as well as privacy. 
The issue is resolved by ``virtual channel'' protocols that, capitalizing on a suitable setup operation, enable the two end-points to engage as if they had a direct payment channel between them.
Beyond communication efficiency, virtual channel constructions have three natural desiderata. 
A virtual channel constructor is {\em recursive} if it can also be applied on pre-existing virtual channels, {\em variadic} if it can be applied on any number of pre-existing channels and {\em symmetric} if it encumbers in an egalitarian fashion all channel participants both in optimistic and pessimistic execution paths. 
We put forth the first bitcoin-suitable recursive virtual channel constructor. 
Furthermore our constructor is variadic and symmetric and offers optimal round complexity both in the optimistic and pessimistic execution paths.  Our virtual channels can be implemented over bitcoin assuming the \texttt{ANYPREVOUT} signature type. 
We express and prove the security of our construction in the universal composition setting.
<br/><br/>

 
### Efficient State Management in Distributed Ledgers
Dimitris Karakostas, University of Edinburgh
<br/><br/>
Distributed ledgers implement a storage layer, on top of which a shared state is maintained in a decentralized manner. 
In UTxO-based ledgers, like Bitcoin, the shared state is the set of all unspent outputs (UTxOs), which serve as inputs to future transactions. 
The continuously increasing size of this shared state will gradually render its maintenance unaffordable. 
Our work investigates techniques that minimize the shared state of the distributed ledger, i.e., the in-memory UTxO set. 
To this end, we follow two directions: a) we propose novel transaction optimization techniques to be followed by wallets, so as to create transactions that reduce the shared state cost and b) propose a novel fee scheme that incentivizes the creation of ``state-friendly'' transactions. 
We devise an abstract ledger model, expressed via a series of algebraic operators, and define the transaction optimization problem of minimizing the shared state; we also propose a multi-layered algorithm that approximates the optimal solution to this problem. 
Finally, we define the necessary conditions such that a ledger's fee scheme incentivizes proper state management and propose a state efficient fee function for Bitcoin.
<br/><br/>

 
### Toward democratising secure decentralised computation
Eleftherios Kokkoris-Kogias, Novi Research and IST Austria
<br/><br/>
While showing great promise, smart contracts are difficult to program correctly, as they need a deep understanding of cryptography and distributed algorithms, and offer limited functionality, as they have to be deterministic and cannot operate on secret data. 
In this talk we present Protean, a general-purpose decentralized computing platform that addresses these limitations by moving from a monolithic execution model, where all participating nodes store all the state and execute every computation, to a modular execution model. 
Protean employs secure specialized side-chains for building decentralized applications that are currently insecure or impossible to implement with smart contracts. 
Each side-chain is a multi-party computation system that provides an efficient implementation of a special-purpose functionality. 
We present three such examples:
* ADKG provides random coins for applications that on the one hand need to abide the deterministic execution of smart-contract and on the other hand require randomisation.
* Calypso  enhances permissioned and permissionless blockchains with the ability to manage confidential data without forfeiting availability or decentralization. 
The proposed architecture addresses two orthogonal challenges confronting modern distributed ledgers: (a) enabling the auditable management of secrets and (b) protecting distributed computations against arbitrage attacks when their results depend on the ordering and secrecy of inputs.
* Brick is the first off-chain construction that remains secure under network asynchrony and concurrently provides correct incentives. While limited in functionality, Protean provides the first comprehensive decentralised system that holds the promise of democratising multi-party computation the way blockchains democratised payments.
<br/><br/>


### FairMM: A Fast and Frontrunning-Resistant Crypto Market-Maker
Michele Ciampi, University of Edinburgh
<br/><br/>
As new and emerging markets, crypto(-currency/-token) markets are susceptible to manipulation and illiquidity. 
The theory of market economics offers market makers that bare the promise of bootstrapping/stabilizing such markets and boosting their liquidity. 
In order, however, to achieve these goals, the market maker operator (typically an exchange) is assumed trusted against manipulations. 
Common attempts to remove/weaken this trust assumption require several on-chain rounds per trade or use expensive MPC machinery, and/or are susceptible to manipulative market-maker operators that perform informed front-running attacks-i.e., manipulate the sequence of trades using future trade information.
In the talk we propose a market-maker-based exchange that is resilient against a wide class of front-running (in particular, reordering attacks). 
When instantiated with a monopolistic profit-seeking market maker our system yields a market where the trading price of crypto-tokens converges to a bid-ask spread centered around their true valuation. 
Importantly, after an initial setup of appropriate smart contracts, the trades are done in an off-chain fashion and smart contracts are invoked asynchronously to the trades. 
Our methodology yields a highly efficient exchange, where the market maker’s compliance is ensured by a combination of a rational market analysis, cryptographic mechanisms, and smart-contract-based collaterals.
<br/><br/>

### Reaching Agreement Without Saying Much: Byzantine Agreement With Polylog Bits Per Party
Ran Cohen, Northeastern University
<br/><br/>
Byzantine agreement (BA), the task of n parties to agree on one of their input bits in the face of malicious agents, is a powerful primitive that lies at the core of a vast range of distributed protocols. Interestingly, in protocols with the best overall communication, the demands of the parties are highly unbalanced: the amortized cost is polylog(n) bits per party, but some parties must send \Omega(n) bits. In best known balanced protocols, the overall communication is sub-optimal, with each party communicating O(\sqrt n) bits.
In this talk, we explore whether asymmetry is inherent for optimizing total communication. We show that this is not the case by presenting two BA protocols where every party communicates only polylog(n) bits; the constructions rely on a new flavor of distributed signatures and offer a tradeoff between setup assumptions and cryptographic assumptions. Next, we will discuss limitations and barriers of this approach, and conclude with open questions.
<br/><br/>


### Formal verification of HotStuff
Leander Jehl, University of Stavanger
<br/><br/>
HotStuff is a recent algorithm for repeated distributed consensus used in permissioned blockchains. We present a simplified version of the HotStuff algorithm and verify its safety using both Ivy and the TLAPS tools.
We show that HotStuff deviates from the traditional view-instance model and instead follows a novel tree model to solve this fundamental problem.
We argue that the tree model results in more complex verification tasks than the traditional view-instance model. Our verification efforts provide initial evidence towards this claim.
<br/><br/>


### Leaderless Byzantine Fault Tolerant State-Machine Replication
Tuanir F. Rezende, Telecom SudParis
<br/><br/>
With the rise of permissioned blockchains, byzantine fault tolerant state-machine replication (BFT-SMR) has gained a lot of traction over the past few years. 
This technique offers stronger safety guarantees and better throughput than solutions running in permissionless environments. 
Unfortunately, it also operates on a much smaller scale which poses a problem in practice.

To address the scalability problem of BFT-SMR, we propose in this talk a new design. Our design is leaderless, replacing the leader that commonly orders state-machine command with a fully decentralized mechanism. 
It consists in a modular framework of two services: a discovery service that computes the concurrent conflicting commands, or dependencies, of a command; and an agreement service that makes these dependencies consensual and durable using a small set of nodes.
We present several instantiations of our framework using well-known techniques (byzantine quorum systems, gossip-based message propagation and threshold cryptography). 
These new BFT-SMR protocols are more scalable than prior art.
They are also more versatile and can adapt easily to the specific needs of the blockchains they power.
<br/><br/>



<!-- ### Participation 

The event is invitation-based and will consist of oral presentations only. There will be no proceedings; abstracts of presented works may appear at the workshop's website. The event is open to all; registration details will be announced soon.

Researchers interested to present new, recent, or ongoing work should submit an abstract for consideration by the Organising Committee at focodile21@corelab.ntua.gr. Contributions from doctoral students and young researchers are particularly encouraged. -->



<!-- ### Important dates
* April 19, 2021: abstract submission
* May 18, 2021: notification
* June 18, 2021: FOCODILE 2021 workshop  -->


### Organising committee
* [Zeta Avarikioti](https://disco.ethz.ch/members/ageorgia) (ETH Zurich)
* [Panagiotis Grontas](http://www.corelab.ntua.gr/~pgrontas/) (National Technical University of Athens)
* [Nikos Leonardos](http://users.uoa.gr/~nleon/) (National and Kapodistrian University of Athens)
* [Aris Pagourtzis](http://users.softlab.ntua.gr/~pagour/), co-chair (National Technical University of Athens)
* [Petros Potikas](http://users.softlab.ntua.gr/~ppotik/), co-chair (National Technical University of Athens)
* [Lewis Tseng](https://www.bc.edu/bc-web/schools/mcas/departments/computer-science/people/faculty-directory/lewis-tseng.html) (Boston College)
* [Vassilis Zikas](https://www.vassiliszikas.com/) (Purdue University)
* [Dionysis Zindros](https://www.dionyziz.com/) (University of Athens)


### More Information
For additional information, please contact the Organising Committee chairs at: focodile21@corelab.ntua.gr