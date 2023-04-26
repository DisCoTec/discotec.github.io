[![](https://www.discotec.org/2023/discotec2023-banner.jpeg)](https://www.discotec.org/2023/)

# Tutorials

The DisCoTec Tutorials focus on emerging topics and aspects of the distributed computing field, ranging from new practical techniques and technologies to lessons learnt from projects and industry experiences.

## An introduction to Spatial Logics and Spatial Model Checking

This tutorial illustrates some emerging aspects of topological spatial and spatio-temporal model checking, going through spatial logics, the language SLCS, current implementation techniques, and some relevant tools and application domains. The audience is provided with a unifying theory of four apparently distant, but intimately related topics: formalization of properties of points in a topological space, identification of nodes in a graph, image segmentation, analysis of 3D meshes.

**Speaker** 

[Vincenzo Ciancia](mailto:vincenzo.ciancia@isti.cnr.it) got his Ph.D. in 2009 with Ugo Montanari. As a post-doc at Univ. Complutense Madrid, ILLC (Amsterdam), IIT-CNR (Pisa), he focused on nominal computation, logic, category theory, process calculi, formal methods. Currently he works at ISTI-CNR Pisa (Formal Methods & Tools lab), on spatial and spatio-temporal model checking, geometric extensions, GPU implementations and HCI issues. He implemented many tools, among which the spatial model checker VoxLogicA, aimed at medical imaging.
<br/><br/>

## A Gentle Adventure Mechanising Message Passing Concurrency Systems

Mechanising programming language metatheory is a hard task. The POPLmark challenge identifies three key problems: (1) reasoning about binders; (2) mechanising complex induction arguments; and (3) building reusable components. In the field of message-passing concurrency, these challenges can be augmented, among other, to: (a) reasoning about linearity; and (b) doing complex coinduction arguments about non-terminating processes.

The aim of this tutorial is to explore a repertoire of techniques that can be used for mechanising the metatheory of session-typed process calculi. We separate this workshop in three parts (acts). In Act I we explore strategies for representing binders in a binary session type system. In Acts II and III we explore reasoning about coinductive processes, in a multiparty process calculus, where Act II focuses on multiparty processes, and Act III on the mechanisation of Multiparty Session Types.

Discussed topics: understanding of basic session types, implementing shallow and deep embeddings in Coq, learning how to use locally nameless (and EMTST), how to mechanise metatheory of session types (both binary and multiparty), and using coinduction for semantic representation of communication systems.

**Speakers**

[David Castro-Perez](d.castro-perez@kent.ac.uk) is a lecturer at the University of Kent. His research is on applying programming language-based techniques to the development of safe and predictable systems, with a strong emphasis on concurrent and distributed systems.

[Francisco Ferreira](francisco.ferreiraruiz@rhul.ac.uk) is a lecturer at Royal Holloway, University of London. His research is on safe and dependable software through a combination of type systems and mechanical proofs. Recently, his work concentrates on session types and mechanical proofs enabling certified software.

[Lorenzo Gheri](l.gheri@imperial.ac.uk) is a research associate (postdoc) at Imperial College London with a background in mathematics, he works on the mechanisation and theory of multiparty session types.

[Martin Vassor](m.vassor@imperial.ac.uk) is a research associate (postdoc) at Imperial College London with a background in computer sciences, he works on the theory and implementation of multiparty session types.
<br/><br/>

## Smart contracts in Bitcoin and BitML

Besides plain transfers of crypto-currency, Bitcoin also allows users to exchange their bitcoins according to pre-agreed rules, i.e. smart contracts. To this purpose, Bitcoin transactions feature a non Turing-complete script language, which is used to specify their redeem conditions. To overcome the limited expressiveness of this language, writing a smart contract in Bitcoin requires devising a protocol through which users can append sequences of transactions in an order consistent with the ideal overall behaviour of the smart contract.

A drawback of this approach is that the complexity of writing smart contracts grows quickly in the number of transactions needed to implement it. Reasoning about the correctness of these contracts is even harder: one would have to consider computational adversaries who interact with the blockchain, only being constrained to use PPTIME algorithms. To overcome these issues we have proposed BitML, a high-level DSL for smart contracts with a computationally sound compiler to Bitcoin transactions.

The computational soundness property allows us to reason about contracts at the symbolic level of the BitML semantics. We exploit this possibility to investigate a landmark property of contracts, called liquidity, which ensures that funds never remain frozen within a contract. In particular, we develop a static analysis for liquidity of BitML contracts.

The tutorial has the following goals:
- compare smart contracts in Bitcoin and in other blockchain platforms, and more in general the UTXO-based and the account-based approaches to blockchain design;
- exemplify the design of smart contracts in Bitcoin
- illustrate how to abstract the Bitcoin transaction mechanism into a high-level contract language, BitML
- give the idea of how to prove the computational soundness of the BitML compiler
- discuss how to enhance the expressiveness of Bitcoin contracts via minor extensions of the transaction mechanism

**Speakers**

[Massimo Bartoletti](mailto:bart@unica.it) is Associate Professor at the Department of Mathematics and Computer Science of the University of Cagliari. His research activity concerns the development of tools and techniques for the specification, analysis and verification of software, with a special emphasis on security. Massimo Bartoletti is founder of the laboratory "Blockchain@Unica" (http://blockchain.unica.it), one of the largest academic research group on blockchain technologies in Italy, director of the node of the Cyber Security National Lab for the University of Cagliari, and core member of the CINI working group on Blockchain. The laboratory is currently investigating several aspects of blockchain technologies, among which custom Domain-Specific Languages for smart contracts. He is principal investigator of several R&D projects on blockchain technologies, editor in chief of the “Smart contracts” section of Frontiers in Blockchains, and member of the scientific board of several workshops on blockchain technologies. 

[Roberto Zunino](mailto:roberto.zunino@unitn.it) is Associate Professor at the Department of Mathematics of the University of Trento. His main research themes are related to the modelling of distributed systems and their verification, employing techniques from concurrency theory, programming languages theory, formal methods, type systems, and static analysis. He is currently researching languages for modelling smart contracts on top of blockchains which do not natively support them, and assessing their security through verification algorithms. He is part of CryptoLabTN, a research group at University of Trento focusing on cryptography and its applications, including blockchain technologies. He is a core member of the Italian Distributed Ledger Technology Working Group, and an associate editor of Frontiers in Blockchain.
<br/><br/>


## The ΔQ Systems Development Paradigm

The ΔQ Systems Development paradigm (ΔQSD) is a novel and industrially-derived software development methodology for developing complex real-world distributed systems, which directly embeds statistically-based performance metrics from the outset of the system design process, and throughout the entire software production life cycle. Its main novelty lies in how it captures the mixture of delay and failure, the continuous and discrete in a single consistent notion.

This paradigm has been developed by PNSol over a period of 20+ years, in collaboration with IOHK, BT, Vodafone, Boeing, Space and Defence, and other major companies who focus on the development of reliable high-quality, high integrity, distributed software systems, with strong real-time requirements.  It has been used to successfully manage performance and architectural tradeoffs in IOHK’s Cardano PoS, as well as being used to perform network service assessments, quantitative analysis of technology and products, in-life optimisation of performance characteristics of broadband network infrastructure. In just the aspect of creating a compositional framework for measurement of network quality, the paradigm has recently been adopted as a new Technical Report (TR 452.1) by the Broadband Forum and is the subject of ongoing standardisation and development effort as part of their QED programme.

Key to the paradigm is that, whilst armed with a strong formal and mathematical basis, it has been developed to serve wider engineering needs. This development was through collaboration with senior technical  personnel. As a result, it can exploit a variety of real-world metrics. The ΔQ paradigm delivers technical depth, simplicity, and ease of understanding via its abstractions that allow direct comparison of performance and reliability between competing designs and implementations. Importantly, it provides a low-cost enhancement to existing functional software verification and testing approaches, that can be expensive and time consuming to deploy. UiB and UCLouvain recently formalised the paradigm by providing a mathematical model that underpins the processes and concerns of systems development a la ΔQ.

In this tutorial, we will present the ΔQ paradigm, highlighting results from a number of large-scale industrial use cases, and providing hands-on introduction to how to use the process in real-world settings.  The tutorial is targeted at researchers, software developers, and managers.

**Speakers**
[Neil Davies](mailto:)
Neil Davies is an expert in resolving the practical and theoretical
challenges of large scale distributed and high-performance computing,
particularly scalability effects in large distributed systems, their
operational quality, and how to manage their degradation gracefully
under saturation and adverse operational conditions. He is a computer
scientist, mathematician and hands-on software developer who builds
rigorously engineered working systems and scalable demonstrators of
new computing and networking concepts.

Throughout his 20-year career at the University of Bristol he was
involved with early developments in networking, its protocols and
their implementations. He collaborated with organisations such as
NATS, Nuclear Electric, HSE, ST Microelectronics and CERN on issues
relating to scalable performance and operational safety. He was also
technical lead on several large EU Framework collaborations relating
to high performance switching, and has mentored PhD candidates at
CERN.

He co-founded Degree2 Innovations in 2000, commercialising network QoS
research, and went on to found Predictable Network Solutions in 2003.
He has worked on performance aspects of the Department of Defense’s
Future Combat Systems project, and has developed approaches to
delivering consistent video telephony for sign language users over
retail broadband. He is the co-author of several patent families.

[Seyed Hossein Haeri](mailto:hossein.haeri@gmail.com) is a Programming Languages scientist with links to both the industry and academia. At the same time that he works for IOHK and Entropy Software Foundation, he is an associate professor at University of Bergen, Norway. Hossein's research is in the intersection between Programming Languages and Software Engineering.
Over the past decade, his research has enjoyed a flavour of Distributed Systems on top.

[Peter Thompson](mailto:) 
Peter Thompson became Chief Technical Officer of Predictable Network
Solutions after several years as Chief Scientist of GoS Networks
Limited (formerly U4EA Technologies). Prior to that he was co-founder
and CEO of Degree2 Innovations, commercialising advanced research into
network QoS undertaken with Neil Davies during the preceding four
years at the Partnership in Advanced Computing Technology in Bristol,
England, where he was a Senior Research Fellow.

Previously he spent eleven years at STMicroelectronics, where one of
his numerous patents for parallel computing and communications
received a corporate World-wide Technical Achievement Award. For five
years he was the Subject Editor for VLSI and Architectures of the
journal Microprocessors and Microsystems, published by Elsevier.

He has degrees in mathematics and physics from the Universities of
Warwick and Cambridge, and spent five years researching general
relativity, twistor theory and quantum theory at the University of
Oxford, supervised by Professor Roger Penrose. He has published papers
and co-authored and co-edited several books on parallel computing and
communications.

He is also chair of the Bristol Energy Cooperative, has the rank of
3rd Dan in Takemusu Aikido, and is a keen choral singer.

In March 2021 he was presented with an Outstanding Contributor Award
at the Broadband Forum virtual Quarterly Meeting.


[Peter Van Roy](mailto:pvr@info.ucl.ac.be)
Peter Van Roy is professor in the ICTEAM Institute at the Université
catholique de Louvain, where he heads the Programming Languages and
Distributed Computing Research Group. He coordinated the EU projects
SELFMAN and LIGHTKONE and was a partner in the projects EMJD-DC,
SYNCFREE, MANCOOSI, EVERGROW, and PEPITO. He is a developer of the
Mozart Programming System and author of a well-known textbook on
computer programming published by MIT Press.

## ChorChain: a Model-driven Approach for Trusted Execution of Multi-party Business Processes on Blockchain

In inter-organizational scenarios, distributed parties that want to reach a common goal need to collaborate by exchanging information. However, this process takes place in untrusted environments, in which correct and secure behaviours cannot be assumed by any of the involved participants. To mitigate this, usually, a trusted third-party monitors and orchestrates the different phases of the collaboration, guaranteeing its right execution. In parallel, blockchain technology was born with the idea of providing a network in which communication takes place without relying on a third party while maintaining the fundamental properties of trust and security. This encouraged the creation of a new form of systems where the business logic is implemented as smart contracts (i.e. programs running inside the blockchain) enforcing the execution of the pre-defined steps.

The tutorial will explore how to implement such systems by exploiting model-driven techniques, necessary to master the technical complexity and to provide an easy-to-use instrument for the system designer.

In particular, we will illustrate the ChorChain framework, which provides indeed an automatic procedure for the generation and execution of smart contracts starting from a high-level specification. As a starting point, the choreography diagram of the BPMN standard is one of the advocated modelling languages able to represent the interactions that should occur among distributed participants.

We will start by introducing the ChorChain framework and its main phases, namely, modelling, instantiation, execution and auditing. Initially, the modelling environment allows participants to design their interactions through the use of a choreography model. Distributed participants can then join it starting the collaboration based on blockchain in an automatic way. After all the roles specified in the model are covered, the execution phase allows participants to exchange information in a secure and immutable way. Finally, thanks to the transparency nature of blockchain, we will show how ChorChain supports process-oriented auditing activities, in which it is possible to retrieve relevant information and monitor the state of the process. During the tutorial, we will refer to real case studies to show the feasibility of the ChorChain framework. 

**Speaker**
[Alessandro Marcelletti](mailto:) is a PhD candidate at the University of Camerino where he obtained his Master's Degree in 2019. His research interests refer to the area of Blockchain technology and its integration into the BPM discipline. His objective is to guarantee secure execution environments between untrusted and distributed business participants. He has also explored the benefits of Blockchain in the IoT sector, creating new forms of trusted systems. His main results involve the creation of different tools and development methodologies based on Blockchain. In these areas, he has published papers in relevant journals and conferences among the other ChorChain framework was published in ACM Transactions on Management Information Systems. He also acts as Co-Organizer and speaker of the 1st  and 2nd International Online Winter School on Blockchain Technology and Applications: Hyperledger, organized online by the University of Camerino.
