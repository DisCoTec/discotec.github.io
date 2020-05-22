[![](https://www.discotec.org/2020/discotec2020-banner.jpeg)](https://www.discotec.org/2020/)

# Invited Speakers

## Nathalie Bertrand 

[INRIA Rennes Bretagne-Atlantique](mailto:nathalie.bertrand@inria.fr)  

###  Probabilistic Threshold Automata for Modeling and Verifying Randomized Distributed Algorithms
 
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

## Holger Hermanns 
[Saarland University](mailto:hermanns@cs.uni-saarland.de)


### Power-Optimal Scheduling of LEO Satellite Networks

Size and weight limitations of Low-Earth Orbit (LEO) small satellites make their operation rest on a fine balance between solar power infeed and power demands of payload and communication technologies on board, buffered by on-board battery storage. As a result, the problem of managing battery-powered payload utilization together with inter-satellite communication is extremely intricate. Nevertheless, there is a growing trend towards constellations and mega-constellations that are to be managed using sophisticated software support.

This invited talk provides a survey of our recent and ongoing work harvesting formal methods research and tool support to master the problem of optimal, effective, scalable, usable, and robust management of LEO satellite networks. We will discuss how timed-automata modelling, dynamic programming, stochastic-kinetic battery representations, receding-horizon scheduling and well-designed abstract programming interfaces play together in the optimal automated management of the GomX-4 satellite family currently in orbit. The approach has been validated in an extensive campaign focussing on applicability, scalability, optimality, and timeliness with respect to the operational requirements and constraints of LEO constellations.

*Joint work with Fakhri Babayev, Morten Bisgaard, Eduardo Cruz, Juan A. Fraire, Carsten Gerstacker, Gilles Nies, Gregory Stock, Tobias Mömke*

### Biography 

Holger Hermanns is Professor in Computer Science at Saarland University in Germany, heading the Dependable Systems and Software group, and Distinguished Professor at Institute of Intelligent Software, Guangzhou. He has previously held positions at Universität Erlangen-Nürnberg, Germany, at Universiteit Twente, the Netherlands, and at INRIA Grenoble Rhône-Alpes, France. His research interests include modeling and verification of concurrent systems, resource-aware embedded systems, compositional performance and dependability evaluation, and their applications to energy informatics. He is an outspoken proponent of proactive algorithmic accountability and distinguished expert on ethics for nerds. Holger Hermanns has authored or co-authored more than 220 peer-reviewed scientific papers (ha-index 92, h-index 54). He co-chaired the program committees of major international conferences such as CAV, CONCUR, TACAS and QEST, and delivered keynotes at about a dozen international conferences and symposia. He serves on the steering committees of ETAPS, LICS and TACAS, is an ERC Advanced Grantee, member of Academia Europaea, spokesperson of TRR 248 on a Science of Perspicuous Computing, and president of the association "Friends of Dagstuhl e.V.".



## Peter Kriens

[OSGi Alliance](mailto:peter.kriens@aqute.biz)

### Formal Specifications to Increase Understanding

I have been active in the Alloy (MIT, Daniel Jackson) community for the last few years. Alloy is an interactive formal specification tool using SAT and SMT to find counterexamples. However, despite my enthusiasm, I am also quite frustrated with how the focus is on the least interesting aspects for me: *proving* the correctness of a specification. It is for me the least interesting because it requires the spec to be correct, which is very hard. However, even harder, it requires the implementation to follow the spec exactly. The people involved in this area seem to leave these all-important aspects as a detail for the practitioners. Instead, they focus on the more  esoteric things like overcoming the combinatorial explosion when proving specifications. 

I think 'something' like Alloy could be eminently useful if it is used to define the semantics of APIs. Today, we define those semantics in comments or, worse, some external Word document. Formally defining service APIs seems to be a low hanging fruit that would boost development productivity significantly. As a developer you spend most of your time trying to understand the domain and testing the tool could generate test case data. Using the service API as an anchor point of such a tool would make it modular, allowing larger specifications that could still be proven. This presentation will explore how such a tool could look like.

### Biography	
  
Peter Kriens has been a software expert consulting for a large number of (some very) large companies like Ericsson, Intel, Adobe, Philips, etc. Over the past 20 years he has been one of the key people in the development of the OSGi specifications: a highly modular µ-service based component model for the Java world. Many innovations in this specification originated from him. Since 1980, he has been highly interested and engaged in finding ways to develop software _better_. He has mentored hundreds of people to do software engineering.  Up to this day, he is still very much driven by the idea that there should be a better way ... He is Dutch, but has been living in Sweden and now in the south of France.









