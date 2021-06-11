[![](https://www.discotec.org/2021/discotec2021-banner.jpeg)](https://www.discotec.org/2021/)

# Invited Speakers

## Alexandra Silva 

[University College London, UK](mailto:alexandra.silva@ucl.ac.uk)  

###  Prognosis: Black-Box Analysis of Network Protocol Implementations

<!-- Presentation 
[slides](./slides/invited/XX and [video](https://youtu.be/6O-CBNBVFV4)
--> 

We present Prognosis, a framework offering automated black-box learning and analysis of models of network protocol implementations. 
Prognosis can learn models that vary in abstraction level from simple deterministic automata to models containing data operations, such as register updates, and can be used to unlock a variety of analysis techniques — model checking temporal properties, computing differences between models of two implementations of the same protocol, or improving testing via model-based test generation. 
Prognosis is modular and easily adaptable to different pro- tocols (e.g., TCP and QUIC) and their implementations. 
We use Prognosis to learn models of (parts of) three QUIC implementations—Quiche (Cloudflare), Google QUIC, and Facebook mvfst—and use these models to analyze the differences between the various implementations. 
Our analysis provides insights into different design choices and uncovers potential bugs. 
Concretely, we have found critical bugs in multiple QUIC implementations, which have been acknowledged by the developers.
This is joint work with Tiago Ferreira (UCL), Harrison Brewton and Loris D’Antoni (University of Wisconsin–Madison).

### Biography
Alexandra Silva is a theoretical computer scientist whose main research focuses on semantics of programming languages and modular development of algorithms for computational models. A lot of her work uses the unifying perspective offered by coalgebra, a mathematical framework established in the last decades.  
Alexandra is currently a Professor of Algebra, Semantics, and Computation at University College London and will be joining Cornell University in the fall of 2021. 
Previously, she was an assistant professor in Nijmegen and a postdoc at Cornell University, with Prof. Dexter Kozen, and a PhD student at the Dutch national research center for Mathematics and Computer Science (CWI), under the supervision of Prof. Jan Rutten and Dr. Marcello Bonsangue. 
She was the recipient of an ERC Consolidator Grant in 2020, the Royal Society Wolfson Award 2019, Needham Award 2018, the Presburger Award 2017, the Leverhulme prize 2016, and an ERC starting Grant in 2015.


## Mira Mezini

[Technical University of Darmstadt, DE](mailto:mezini@st.informatik.tu-darmstadt.de)

### Let it Flow:  Reactive Computations for Consistent-by-Design Distributed Applications

<!--Presentation [video](https://www.youtube.com/watch?v=na89OTNe-xo) -->

Ubiquitous connectivity of millions of powerful (mobile) devices to each other and to web and cloud computing platforms via programmable networks has created globally and massively distributed computing systems---the information power grids of the 21st century---and has fuelled the development of massively distributed applications.  
Today, distributed applications often rely on centralized servers/clouds for consistency management. 
However, centralized consistency management is not a good match for massively distributed computing systems due to problems with offline availability, low latency, or user-control on data privacy, etc. 
Decentralized architectures with decentralized state and local-first computations are a better match for globally distributed computing systems. 
However, when building applications for such architectures, developers are left with the responsibility of handling partial failures at the application layer, thereby trading off between high availability and strong consistency. 

In the talk, I will argue for and discuss language-based solutions automating hybrid consistency decisions. 
With such solutions, it is the responsibility of the language machinery to reason about consistency levels and to make use of hybrid consistency systems as needed by the application semantics. 
As a result, such languages offer developers well-defined and formally-proven guarantees “out-of-the-box”. 
I will specifically focus on how declarative reactive programming abstractions help in automatically handling the challenges of decentralization by providing decentralized concurrency control and fault-tolerance with well-defined consistency guarantees. I will present my thoughts in the context of REScala (rescala-lang.com)---a library-based extension to the programming language Scala---that my team and me have designed and implemented in the recent past. 
In the reactive style of REScala, applications are modelled as compositions of reactive abstractions, which denote time-changing values resulting from computations with reactive application semantics (i.e., computations are automatically executed whenever their inputs change). 
I will elaborate on how this model in synergetic combination with concepts from multi-version consistency control, asynchronous distributed computing, and invariant-based verification enable a language-based management of application consistency in concurrent and distributed settings with well-defined guarantees.    

### Biography

Mira Mezini obtained a doctorate degree from the University of Siegen (Germany) in 1997 and was visiting assistant professor at Northeastern University (USA), before becoming professor of computer science at Technical University of Darmstadt (Germany) in 2000. 
From 2013 to 2016, she additionally held a visiting professorship at Lancaster University (UK). 
Mira leads the chair for software technology at TU Darmstadt. 
Her research focuses in software analysis and programming language design with applications in networked software systems, software security, and AI systems.  
Mira Mezini was selected to the German Academy of Science and Engineering (acatech) in 2016. 
She has received various research awards, including two IBM Innovation Awards, a Google Research Award, and most notably FGan ERC Advanced Grant in 2013, the EU's most highly endowed funding award. 
Has published more than 180 papers, many of which in top venues across the areas of programming languages and software engineering, and serves regularly in program committees and editorial boards of conferences and journals in these areas.



## Gilles Fedak

[iExec, FR](mailto:gilles.fedak@iex.ec)

### iExec: Building a Decentralized, Trusted and Privacy-Preserving Computing Infrastructure

<!--Presentation [video](https://youtu.be/paePTldDhwY) -->

iExec is a French startup company based in Lyon which built the first decentralized marketplace in which entities (e.g. traditional cloud providers, research centers and even individuals) can contribute and monetize Cloud Computing resources (CPU, GPU), Decentralized Applications (Dapps) and data-sets (Data Renting) in a secure and confidential way, ensuring the confidentiality and ownership of data.
During this talk, I will present how iExec combines Ethereum Smart Contracts, a unique Proof-of-Contribution (PoCo) protocol and Trusted Execution Environments (TEE) to ensure trust between providers and consumers of resources. 
The project, however, is still facing several scientific and technological barriers related to scalability, interoperability and to supporting more classes of applications. 
I will discuss several research topics (e.g. ZK-proofs and rollups) and two H2020 projects in which iExec is involved: OntoChain, which aims at building a trusted and transparent knowledge management ecosystem and Datacloud, which goal is to build a platform for big data analytics in the edge-to-cloud continuum.

### Biography

Gilles Fedak is CEO and co-founder of iExec: Blockchain-based Decentralized Cloud Computing. 
iExec issued the RLC token and realized the first major ICO in France on April 19th, 2017, raising 10.000 Bitcoins (equivalent to 12.5 million USD) in less than 3 hours. 
iExec builds a decentralized market place for computing resources using the Ethereum blockchain, and has been a permanent Inria research scientist since 2004 at the ENS in Lyon, France. 
After receiving his Ph.D degree from the University of Paris Sud in 2003, he followed a postdoctoral fellowship at the University of California in San Diego in 2003-2004. 
His research interests lie in Parallel and Distributed Computing, with a particular emphasis on the problematic of using large and loosely-coupled distributed computing infrastructures to support highly demanding computational and data-intensive science. 
Gilles produced pioneering software and algorithms in the field of Grid and Cloud Computing that allow people to easily harness large parallel systems consisting of thousands of machines distributed on the Internet (XtremWeb, MPICH-V, BitDew, SpeQulos, Xtrem-MapReduce, and Active Data). 
He co-authored about 80 peer-reviewed scientific papers and won two Best Paper awards. 
In 2012, G. Fedak co-edited with C. Cérin the Desktop Grid Computing Book, (CRC publication), and in 2015, he received the Chinese Academy of Sciences PIFI Award.


## Helene Coullon

[IMT Atlantique, FR](mailto:helene.coullon@imt-atlantique.fr)

### Execution and Planning of Distributed Systems Reconfigurations - Concurrency and formal aspects

Large distributed software systems are nowadays built in a component-based approach (e.g., service-oriented architectures or microservices) that offers a convenient way to structure large applications. 
Indeed, isolating functionalities in components and building systems through composition greatly enhances the adaptability and scalability of applications, two important requirements for many organizations. 
This approach is also promoted by the massive adoption of highly distributed computing infrastructures such as cloud and edge computing. 
However, the advantages of distributed architectures come at the price of increased complexity and an array of technical challenges related to observability, coordination, maintenance, etc. For many years deployment and management procedures were written in an ad-hoc fashion through "readme" files and bash scripts and very was often triggered manually by an operator. 
But, in recent years the DevOps community (both from academia and industry) has significantly improved this area by bringing programming support and software engineering properties to distributed software management.
In this talk, I will explore, through three main contributions, the concept of reconfiguration of component-based distributed systems, in particular, the planning and execution of such reconfiguration. 
These topics will be studied from two perspectives: the concurrency and efficiency of reconfiguration; and formal and safety aspects of reconfiguration.
To this end, I will first present the formal reconfiguration model Concerto in which: (1) the lifecycle of each component is programmable with concurrency, and (2) reconfigurations are constructed by composing component lifecycles and submitting asynchronous behavior requests to components. 
Next, I will present a contribution that uses timed Petri nets and model checking to ensure qualitative and quantitative properties on a subset of Concerto. 
Finally, I will present an ongoing work on the automatic synthesis, by using SMT (Satisfiability Modulo Theories), of Concerto reconfiguration procedures from a partial target configuration.

### Biography

Helene Coullon started her career in 2007 as a development engineer in the French company Dassault Systems where she was in charge of internal continuous integration tools, and parallel compilation processes. After two years she decided to start a career in academia, first as a research engineer for two years, and then as a PhD student for three years. The PhD was funded by the company Antea Group and has been defended at the University of Orléans in France in September 2014. Helene has designed a domain specific framework to automatically execute on high performance computing (HPC) clusters numerical simulations written in C++. She then worked for two years as a postdoctoral researcher at Inria in the Avalon team in Lyon, where she designed a domain specific language that leverages the component-based model L2C with the work achieved during her PhD to enhance reusability and separation of concerns in HPC codes. 
Helene Coullon is associate professor in computer science at IMT Atlantique since 2016, and an Inria researcher (under a chair from 2016 to 2021) in the STACK research Team (Inria, IMTA DAPI, LS2N). 
She is also adjunct professor at the University of Tromsø (Norway) in the DAO project led by Otto Anshus since 2020. Her current research topics are programming models in the context of distributed infrastructures and systems. 
In particular, she is interested in configuration, deployment, reconfiguration, and dynamic adaptation of large and complex distributed software systems.



## Lewis Tseng

[Boston College, USA](mailto:lewis.tseng@bc.edu)

### High-performance crash-tolerant SMR in a single datacenter

State-Machine Replication (SMR) uses replication to ensure that a service is available and consistent in the presence of failures. One popular mechanism for implementing SMR is to use a consensus algorithm to agree on the total order of client requests, namely, a log-based SMR approach. I will present our recent works on improving log-based SMR deployed in a single datacenter:
 
(i) in the first work, we use randomization to simplify the design. Compared to Multi-Paxos and EPaxos, our system maintains high performance with reduced engineering complexity, by exploiting the stable network infrastructure in a single datacenter.
 
(ii) in the second work, we port Paxos to our new model which exploits the power of remote direct memory access (RDMA). Our system offers good performance while demonstrating better tail latency and faster fail-over compared to a state-of-the-art competitor.


### Biography

Lewis Tseng is an assistant professor in the Computer Science department at Boston College. 
Before that, he spent a year and a half as a researcher at Toyota InfoTechnology Center. 
He received a B.S. and a Ph.D. degree both in Computer Science from the University of Illinois at Urbana-Champaign (UIUC) in 2010 and 2016, respectively. 
His research broadly lies in the intersection of fault-tolerant computing and distributed computing. H
e won the best paper award in the International Symposium on Stabilization, Safety, and Security of Distributed Systems (SSS) 2017. 
He has served in many program committees including ICDCN 2018, SIROCCO 2018, PODC 2020, ICDCS 2021, DISC 2021, etc. 