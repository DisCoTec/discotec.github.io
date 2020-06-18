[![](https://www.discotec.org/2020/discotec2020-banner.jpeg)](https://www.discotec.org/2020/)

# Invited Speakers

## Nathalie Bertrand 

[INRIA Rennes Bretagne-Atlantique](mailto:nathalie.bertrand@inria.fr)  

###  Probabilistic Threshold Automata for Modeling and Verifying Randomized Distributed Algorithms

<br/>
Presentation slides [(all)](./slides/invited/DisCoTec20-NB.pdf)
<br/>
Presentation video [YouTube](https://www.youtube.com/watch?v=xIOk6rFQkAc&feature=youtu.be)
 
Randomisation is a powerful tool to solve computationally hard problems: in
distributed computing, probabilities can even permit to solve problems that are
otherwise unsolvable, such as the consensus problem for asynchronous message-
passing systems. 
Threshold automata were introduced by Konnov et al. to automatically prove
safety and liveness properties in fault-tolerant non-probabilistic distributed
algorithms. They fall short at representing randomized behaviours and algorithms
working in rounds. We introduced a probabilistic variant of threshold automata,
and designed model-checking algorithms to automatically verify whether given
properties hold almost-surely (i.e. with probability 1). These are first steps
towards the automated verification of randomised distributed algorithms. 

### Biography
Nathalie Bertrand got her PhD degree from ENS Cachan in 2006. Since 2007, she is
Inria researcher at IRISA Rennes. Her expertise lies in formal methods, in
particular model checking, with a special focus on probabilistic models.



## Cinzia Di Giusto

[(Université Côte d’Azur, CNRS, I3S, France)](mailto:cinzia.di-giusto@unice.fr)

### On the k-synchronizability of Distributed Systems

<br/>
<!-- Presentation slides [(all)](./slides/invited/) -->
Presentation slides to be linked soon
<!-- <br/>
Presentation video [YouTube](https://youtu.be/v3S6lhKOFPU) -->

I will discuss the notion of k-synchronizability: a system is k-synchronizable if any of its executions, up to reordering causally independent actions, can be divided into a succession of k-bounded interaction phases. We know that the reachability problem is decidable for k-synchronizable systems. Moreover, the membership problem (whether a system is k-synchronizable for a given k) is decidable as
well. Our proofs fix several important issues in previous attempts to prove these two results for mailbox automata. Finally, I will point our last results on deciding whether there exists a k such that a system is k-synchronizable.

### Biography

Dr Cinzia Di Giusto received her PhD in Computer Science from the University of Bologna in 2009. She held post-doc positions at Inria-Grenoble (2010-2011) working on the modelling of components with concurrent languages, CEA (2012) on the modelling of reversible structures with categories, and University of Evry (2013) on the modelling and verification of bioinspired models. She joined the University of Nice-Sophia Antipolis (I3S Laboratory) in 2014 as associate professor. Her research interests hinge on the modelling and verification of concurrent and timed systems, especially using process algebra, behavioural types, rewriting systems, Petri nets and more recently communicating automata.


## Holger Hermanns 
[Saarland University](mailto:hermanns@cs.uni-saarland.de)

### Power-Optimal Scheduling of LEO Satellite Networks

<br/>
Presentation slides [(all)](./slides/invited/2020-06-18-holger-hermanns-discotec-malta.pdf)
<br/>
Presentation video [YouTube](https://youtu.be/kHEi6ViqPoc)

Size and weight limitations of Low-Earth Orbit (LEO) small satellites make their operation rest on a fine balance between solar power infeed and power demands of payload and communication technologies on board, buffered by on-board battery storage. As a result, the problem of managing battery-powered payload utilization together with inter-satellite communication is extremely intricate. Nevertheless, there is a growing trend towards constellations and mega-constellations that are to be managed using sophisticated software support.

This invited talk provides a survey of our recent and ongoing work harvesting formal methods research and tool support to master the problem of optimal, effective, scalable, usable, and robust management of LEO satellite networks. We will discuss how timed-automata modelling, dynamic programming, stochastic-kinetic battery representations, receding-horizon scheduling and well-designed abstract programming interfaces play together in the optimal automated management of the GomX-4 satellite family currently in orbit. The approach has been validated in an extensive campaign focussing on applicability, scalability, optimality, and timeliness with respect to the operational requirements and constraints of LEO constellations.

*Joint work with Fakhri Babayev, Morten Bisgaard, Eduardo Cruz, Juan A. Fraire, Carsten Gerstacker, Gilles Nies, Gregory Stock, Tobias Mömke*

### Biography 

Holger Hermanns is Professor in Computer Science at Saarland University in Germany, heading the Dependable Systems and Software group, and Distinguished Professor at Institute of Intelligent Software, Guangzhou. He has previously held positions at Universität Erlangen-Nürnberg, Germany, at Universiteit Twente, the Netherlands, and at INRIA Grenoble Rhône-Alpes, France. His research interests include modeling and verification of concurrent systems, resource-aware embedded systems, compositional performance and dependability evaluation, and their applications to energy informatics. He is an outspoken proponent of proactive algorithmic accountability and distinguished expert on ethics for nerds. Holger Hermanns has authored or co-authored more than 220 peer-reviewed scientific papers (ha-index 92, h-index 54). He co-chaired the program committees of major international conferences such as CAV, CONCUR, TACAS and QEST, and delivered keynotes at about a dozen international conferences and symposia. He serves on the steering committees of ETAPS, LICS and TACAS, is an ERC Advanced Grantee, member of Academia Europaea, spokesperson of TRR 248 on a Science of Perspicuous Computing, and president of the association "Friends of Dagstuhl e.V.".


## Peter Kriens

[OSGi Alliance](mailto:peter.kriens@aqute.biz)

### Formal Specifications to Increase Understanding

<br/>
<!-- Presentation slides [(all)](./slides/invited/) -->
Presentation slides to be linked soon
<br/>
Presentation video [YouTube](https://www.youtube.com/watch?v=_j3SdIGqYG8&feature=youtu.be)

I have been active in the Alloy (MIT, Daniel Jackson) community for the last few years. Alloy is an interactive formal specification tool using SAT and SMT to find counterexamples. However, despite my enthusiasm, I am also quite frustrated with how the focus is on the least interesting aspects for me: *proving* the correctness of a specification. It is for me the least interesting because it requires the spec to be correct, which is very hard. However, even harder, it requires the implementation to follow the spec exactly. The people involved in this area seem to leave these all-important aspects as a detail for the practitioners. Instead, they focus on the more  esoteric things like overcoming the combinatorial explosion when proving specifications. 

I think 'something' like Alloy could be eminently useful if it is used to define the semantics of APIs. Today, we define those semantics in comments or, worse, some external Word document. Formally defining service APIs seems to be a low hanging fruit that would boost development productivity significantly. As a developer you spend most of your time trying to understand the domain and testing the tool could generate test case data. Using the service API as an anchor point of such a tool would make it modular, allowing larger specifications that could still be proven. This presentation will explore how such a tool could look like.

### Biography	
  
Peter Kriens has been a software expert consulting for a large number of (some very) large companies like Ericsson, Intel, Adobe, Philips, etc. Over the past 20 years he has been one of the key people in the development of the OSGi specifications: a highly modular µ-service based component model for the Java world. Many innovations in this specification originated from him. Since 1980, he has been highly interested and engaged in finding ways to develop software _better_. He has mentored hundreds of people to do software engineering.  Up to this day, he is still very much driven by the idea that there should be a better way ... He is Dutch, but has been living in Sweden and now in the south of France.



## Karoliina Lehtinen

[University of Liverpool](mailto:k.lehtinen@liverpool.ac.uk)

### Parity Games: The Quasi-polynomial Era

<br/>
<!-- Presentation slides [(all)](./slides/invited/) -->
Presentation slides to be linked soon
<!-- <br/>
Presentation video [YouTube](https://youtu.be/TjGBEfjKoJ0) -->

Parity games are central to the verification and synthesis of reactive systems: various model-checking and synthesis problems reduce to solving these games. Solving parity games -- that is, deciding which player has a winning strategy -- is one of the few problems known to be in both UP and co-UP yet not known to be in P. So far, the quest for a polynomial algorithm has lasted over 25 years.

In 2017 a major breakthrough occurred: parity games are solvable in quasi-polynomial time. Since then, several seemingly very distinct quasi-polynomial algorithms have been published, both by myself and others, and some of the novel ideas behind them have been applied to address other verification problems.

This talk takes you on a high-level tour of what has been going on in the world of parity games since 2017 and where we are now. I will present one particularly straight-forward quasi-polynomial algorithm in more detail.

### Biography

Dr Karoliina Lehtinen is a Marie Skłodowska-Curie fellow at the University of Liverpool. Her main research interests are logic, games and automata in the context of verification. While she is perhaps best-known for her work on parity games and automata on infinite words, her research also spans topics such as synthesis and runtime verification. She did her doctorate on the modal mu calculus at the University of Edinburgh, UK. She then spent two years at the University of Kiel, Germany, as a postdoc, punctuated by a couple of months at IDC Herzliya, Israel, before moving to Liverpool, back in the UK.



## Kenneth McMillan

[Microsoft Research Lab Redmond](mailto:kenmcmil@microsoft.com)

### Ivy: A Verification Tool for Distributed Algorithms

<br/>
<!-- Presentation slides [(all)](./slides/invited/) -->
Presentation slides to be linked soon
<br/>
Presentation video [YouTube](https://www.youtube.com/watch?v=gR8xRg_EqDI&feature=youtu.be)

Ivy is an open-source, multi-modal verification tool for correct design and implementation of distributed algorithms, supporting modular
specification, implementation and proof. The motivating principles of Ivy are predictability, stability and transparency. That is, automated proof steps should provide complexity bounds, should be insensitive to small perturbations, and when they fail should provide actionable feedback.  To the extent consistent with these principles, Ivy aims to maximize expressiveness and proof automation, and thus to achieve a high level of user
productivity in designing, implementing and proving distributed programs.

I will describe the principles of Ivy's design and describe how to use Ivy effectively to implement a verified distributed protocol.

### Biography	

Ken McMillan is a researcher at Microsoft Research in Redmond, Washington.  He works in formal verification and light-weight formal methods, particularly in applications to hardware and distributed protocols. His main interest is in tools, languages and methodologies that can be applied practically in an engineering environment. His current work in verification centers on a tool called Ivy, whose design goal is to make maximally effective use of proof automation in
the verification of distributed systems. His past work includes the development of Symbolic Model Checking and Craig interpolation methods in model checking. He holds a BS in electrical engineering from the University of Illinois at Urbana (1984), an MS in electrical engineering from Stanford (1986) and a Ph.D. in computer science from Carnegie Mellon (1992). He is the author of the book "Symbolic Model Checking", and the SMV symbolic model checking system.  For his work
in model checking, he has received the ACM doctoral dissertation award, the SRC technical excellence award, the ACM Paris Kannelakis award, the Alan Newell award from Carnegie Mellon and the CAV award. He was formerly a member of the technical staff at AT&T Bell Laboratories and a fellow at Cadence Research Labs.

## Vassilis Zikas

[University of Edinburgh](mailto:vzikas@inf.ed.ac.uk)

###  From Blockchain to Global-Scale Trustworthy Infrastructure

<br/>
<!-- Presentation slides [(all)](./slides/invited/) -->
Presentation slides to be linked soon
<!-- <br/>
Presentation video [YouTube](https://youtu.be/X3cG6-t9sJo) -->

The wide adoption of global computer networks, such as the Internet, creates immense opportunities, and challenges the traditional centralized trust model. The idea of giving control of widely-used critical infrastructure to its users is becoming ever more popular. Blockchain and Distributed Ledger Technology (DLT) promise to bring the decentralization ideas to reality and disrupt traditional strongholds of trust in the financial, digital, biomedical, and manufacturing sectors, as well as in governance. This talk will discuss the basic principles of blockchain-based DLT, and how intensive research in cryptography, security, and distributed systems paves the path to global and sustainable decentralization. I will discuss novel design choices that go into blockchain-based DLT, and how these choices critically impact the security of the solutions and address implementation and deployment challenges. The talk will be self-contained and accessible to the general CS audience.


### Biography 

Prof. Vassilis Zikas is an Associate Professor (Sr. Lecturer) and the Vice Director of the Blockchain Technology Lab at the University of Edinburgh. His research on blockchain and cryptocurrencies has been published at the top venues in cryptography and security, and is being deployed in popular blockchain systems. Prior to his current appointment, Vassilis was a tenure-track Assistant Professor at RPI, Troy, NY, a Research Fellow at Simons Institute, UC Berkeley, a Senior Researcher at ETH Zurich, and postdoctoral researcher at UCLA and the University of Maryland. He has also been a research fellow and area leader for the leading research-and-development blockchain company IOHK and has received substantial industry support for his research on blockchain and decentralized ledgers. Vassilis is the recipient of a highly selective career development grant by the Swiss NSF, a Simons Institute Fellowship, and a Swiss NSF Fellowship.







