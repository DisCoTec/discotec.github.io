[![](https://www.discotec.org/2022/discotec2022-banner.jpeg)](https://www.discotec.org/2022/)

# Tutorials

The DisCoTec Tutorials focus on emerging topics and aspects of the distributed computing field, ranging from new practical techniques and technologies to lessons learnt from projects and industry experiences.

## An introduction to Spatial Logics and Spatial Model Checking

This tutorial illustrates some emerging aspects of topological spatial and spatio-temporal model checking, going through spatial logics, the language SLCS, current implementation techniques, and some relevant tools and application domains. The audience is provided with a unifying theory of four apparently distant, but intimately related topics: formalization of properties of points in a topological space, identification of nodes in a graph, image segmentation, analysis of 3D meshes.

**Speaker's Biography:** 

[Vincenzo Ciancia](mailto:vincenzo.ciancia@isti.cnr.it) got his Ph.D. in 2009 with Ugo Montanari. As a post-doc at Univ. Complutense Madrid, ILLC (Amsterdam), IIT-CNR (Pisa), he focused on nominal computation, logic, category theory, process calculi, formal methods. Currently he works at ISTI-CNR Pisa (Formal Methods & Tools lab), on spatial and spatio-temporal model checking, geometric extensions, GPU implementations and HCI issues. He implemented many tools, among which the spatial model checker VoxLogicA, aimed at medical imaging.

## A Gentle Adventure Mechanising Message Passing Concurrency Systems

Mechanising programming language metatheory is a hard task. The POPLmark challenge identifies three key problems: (1) reasoning about binders; (2) mechanising complex induction arguments; and (3) building reusable components. In the field of message-passing concurrency, these challenges can be augmented, among other, to: (a) reasoning about linearity; and (b) doing complex coinduction arguments about non-terminating processes.

The aim of this tutorial is to explore a repertoire of techniques that can be used for mechanising the metatheory of session-typed process calculi. We separate this workshop in three parts (acts). In Act I we explore strategies for representing binders in a binary session type system. In Acts II and III we explore reasoning about coinductive processes, in a multiparty process calculus, where Act II focuses on multiparty processes, and Act III on the mechanisation of Multiparty Session Types.

Discussed topics: understanding of basic session types, implementing shallow and deep embeddings in Coq, learning how to use locally nameless (and EMTST), how to mechanise metatheory of session types (both binary and multiparty), and using coinduction for semantic representation of communication systems.

**Speakers' Biography:**

[David Castro-Perez](d.castro-perez@kent.ac.uk) is lecturer at the University of Kent. His research is on applying programming language-based techniques to the development of safe and predictable systems, with a strong emphasis on concurrent and distributed systems.

[Francisco Ferreira](francisco.ferreiraruiz@rhul.ac.uk) is lecturer at Royal Holloway, University of London. His research is on safe and dependable software through a combination of type systems and mechanical proofs. Recently, my work concentrates on session types and mechanical proofs enabling certified software.

[Lorenzo Gheri](l.gheri@imperial.ac.uk) is research Associate (postdoc) at Imperial College London with a background in mathematics, he works on the mechanisation and theory of multiparty session types.

[Lorenzo Gheri](l.gheri@imperial.ac.uk) is a research Associate (postdoc) at Imperial College London with a background in mathematics, he works on the mechanisation and theory of multiparty session types.

### Smart contracts in Bitcoin and BitML

Besides plain transfers of crypto-currency, Bitcoin also allows users to exchange their bitcoins according to pre-agreed rules, i.e. smart contracts. To this purpose, Bitcoin transactions feature a non Turing-complete script language, which is used to specify their redeem conditions. To overcome the limited expressiveness of this language, writing a smart contract in Bitcoin requires devising a protocol through which users can append sequences of transactions in an order consistent with the ideal overall behaviour of the smart contract.

A drawback of this approach is that the complexity of writing smart contracts grows quickly in the number of transactions needed to implement it. Reasoning about the correctness of these contracts is even harder: one would have to consider computational adversaries who interact with the blockchain, only being constrained to use PPTIME algorithms. To overcome these issues we have proposed BitML, a high-level DSL for smart contracts with a computationally sound compiler to Bitcoin transactions.

The computational soundness property allows us to reason about contracts at the symbolic level of the BitML semantics. We exploit this possibility to investigate a landmark property of contracts, called liquidity, which ensures that funds never remain frozen within a contract. In particular, we develop a static analysis for liquidity of BitML contracts.

The tutorial has the following goals:
- compare smart contracts in Bitcoin and in other blockchain platforms, and more in general the UTXO-based and the account-based approaches to blockchain design;
- exemplify the design of smart contracts in Bitcoin
- illustrate how to abstract the Bitcoin transaction mechanism into a high-level contract language, BitML
- give the idea of how to prove the computational soundness of the BitML compiler
- discuss how to enhance the expressiveness of Bitcoin contracts via minor extensions of the transaction mechanism

**Speakers' Biography:**

[Massimo Bartoletti](mailto:bart@unica.it) is Associate Professor at the Department of Mathematics and Computer Science of the University of Cagliari. His research activity concerns the development of tools and techniques for the specification, analysis and verification of software, with a special emphasis on security. Massimo Bartoletti is founder of the laboratory "Blockchain@Unica" (http://blockchain.unica.it), one of the largest academic research group on blockchain technologies in Italy, director of the node of the Cyber Security National Lab for the University of Cagliari, and core member of the CINI working group on Blockchain. The laboratory is currently investigating several aspects of blockchain technologies, among which custom Domain-Specific Languages for smart contracts. He is principal investigator of several R&D projects on blockchain technologies, editor in chief of the “Smart contracts” section of Frontiers in Blockchains, and member of the scientific board of several workshops on blockchain technologies. 

[Roberto Zunino](mailto:roberto.zunino@unitn.it) is Associate Professor at the Department of Mathematics of the University of Trento. His main research themes are related to the modelling of distributed systems and their verification, employing techniques from concurrency theory, programming languages theory, formal methods, type systems, and static analysis. He is currently researching languages for modelling smart contracts on top of blockchains which do not natively support them, and assessing their security through verification algorithms. He is part of CryptoLabTN, a research group at University of Trento focusing on cryptography and its applications, including blockchain technologies. He is a core member of the Italian Distributed Ledger Technology Working Group, and an associate editor of Frontiers in Blockchain.


### Performance evaluation of networks, grids, and clouds by colored Petri nets

A network should be correct and efficient. While the correctness of networks functioning is established through the verification of networking protocols, the network efficiency is estimated in the process of performance evaluation using either analytical methods or simulation, or both. A classical Petri net is applied for verification of networking protocols. A colored Petri net, that represents a union of a Petri net graph and a functional programming language, is a convenient and flexible tool for simulating networks, grids, and clouds. Using special measurement components of colored Petri nets allows us to obtain performance and QoS characteristics directly in the process of simulation. A series of colored Petri net models has been developed for simulating Ethernet, IP, MPLS, Bluetooth, and PBB networks, square and multidimensional (hypercube and hypertorus) grids. Performance evaluation is a necessary stage of a network design for real-time applications. Recently multidimensional torus is applied as the topology of communication systems of supercomputers and clusters, for instance the most powerful supercomputer Fugaku of Fujitsu uses Tofu Interconnect D having topology of 6D torus.

We will focus on the technique for modeling networks, grids, and clouds by colored Petri nets in the environment of modeling system CPN Tools (http://cpntools.org). Manifold publications and real life projects acknowledge such advantages of modeling by colored Petri nets as: vivid graphical form of representation, high descriptive power, flexibility, and convenience of use. Firstly, we will create a model of a given network, using early created components for networks, debug it and observe the process of generating and delivering packets, check corresponding routing/switching tables and algorithms of their creation. Random distribution functions are widely applied for modeling the network traffic and packets processing within network and computing nodes. Secondly, we will supply the model with specially-designed measuring components to estimate the network performance and QoS directly in the process of simulation.

The tutorial is supported by teaching materials freely downloaded from the web-site of the tutor. 

**Speaker's Biography:**

[Dmitry A. Zaitsev](mailto:zsoftua@yahoo.com) received the Eng. degree in Applied Mathematics from Donetsk Polytechnic Institute, Donetsk, Ukraine, in 1986, the Ph.D. degree in Automated Control from the Kiev Institute of Cybernetics, Kiev, Ukraine, in 1991, and the Dr.Sc. degree in Telecommunications from the Odessa National Academy of Telecommunications, Odessa, Ukraine, in 2006. He developed the analysis of infinite Petri nets with regular structure, the decomposition of Petri nets in clans, generalized neighborhood for cellular automata, and the method of synthesis of fuzzy logic function given by tables. He developed Opera-Topaz software for manufacture operative planning and control; a new stack of networking protocols E6 and its implementation within Linux kernel; Petri net analysis software Deborah, Adriana, and ParAd; models of TCP, BGP, IOTP protocols, Ethernet, IP, MPLS, PBB, and Bluetooth networks. His current research interests include Petri net theory and its application in networking, computing and automated manufacture. Recently he started working in the area of exascale computing applying his theory of clans to speed-up solving sparse linear systems on parallel and distributed architectures. He was a co-director of joint projects with China and Austria. Recently he has been a visiting professor to Technical University of Dortmund, Germany on DAAD scholarship, to University of Tennessee Knoxville, USA on Fulbright scholarship and to Eindhoven University of Technology, Netherlands. He published a monograph, 3 book chapters and more than a hundred of papers including issues listed in JCR. He is a senior member of ACM and IEEE. Additional information including papers, software, models, video-lectures in put on personal website via http://daze.ho.ua 

## The ΔQ Systems Development Paradigm

The ΔQ Systems Development paradigm (ΔQSD) is a novel and industrially-derived software development methodology for developing complex real-world distributed systems, which directly embeds statistically-based performance metrics from the outset of the system design process, and throughout the entire software production life cycle. Its main novelty lies in how it captures the mixture of delay and failure, the continuous and discrete in a single consistent notion.

This paradigm has been developed by PNSol over a period of 20+ years, in collaboration with IOHK, BT, Vodafone, Boeing, Space and Defence, and other major companies who focus on the development of reliable high-quality, high integrity, distributed software systems, with strong real-time requirements.  It has been used to successfully manage performance and architectural tradeoffs in IOHK’s Cardano PoS, as well as being used to perform network service assessments, quantitative analysis of technology and products, in-life optimisation of performance characteristics of broadband network infrastructure. In just the aspect of creating a compositional framework for measurement of network quality, the paradigm has recently been adopted as a new Technical Report (TR 452.1) by the Broadband Forum and is the subject of ongoing standardisation and development effort as part of their QED programme.

Key to the paradigm is that, whilst armed with a strong formal and mathematical basis, it has been developed to serve wider engineering needs. This development was through collaboration with senior technical  personnel. As a result, it can exploit a variety of real-world metrics. The ΔQ paradigm delivers technical depth, simplicity, and ease of understanding via its abstractions that allow direct comparison of performance and reliability between competing designs and implementations. Importantly, it provides a low-cost enhancement to existing functional software verification and testing approaches, that can be expensive and time consuming to deploy. UiB and UCLouvain recently formalised the paradigm by providing a mathematical model that underpins the processes and concerns of systems development a la ΔQ.

In this tutorial, we will present the ΔQ paradigm, highlighting results from a number of large-scale industrial use cases, and providing hands-on introduction to how to use the process in real-world settings.  The tutorial is targeted at researchers, software developers, and managers.

**Speakers' Biography:**

[Kevin Hammond]() 


[Philipp Kant]()