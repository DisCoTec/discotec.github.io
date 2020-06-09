[![](https://www.discotec.org/2020/discotec2020-banner.jpeg)](https://www.discotec.org/2020/)

# Tutorials

## Scope

The DisCoTec Tutorial Day allows researchers to promote a *mature* tool that has been under development over the last few years. 
Tutorial session are typically *hands-on*, providing the audience with the unique opportunity to try out the tool under the supervision of those who developed it. This rewards the tool developers for the effort invested in making their tool accessible to the community, fosters cross-fertilisation across the three DisCoTec conferences, and ultimately results in a higher adoption of the presented tools.

## Titles


### Choreographic Development of Message-Passing Applications

Choreography envisages distributed coordination as determined by interactions that allow peer components to harmoniously realise a given task. Unlike in orchestration-based coordination, there is no special component directing the execution. 
Recently choreographic approaches became popular in industrial contexts where reliability and scalability are crucial factors. This tutorial will review some recent ideas to harness choreographic development of message-passing software.
<br/> <br/>
*Biography:* 
Emilio Tuosto is an associate professor at the Gran Sasso Science Institue and the University of Leicester. He graduated (1998) and got his PhD degree in Computer Science (2003) at the department of Computer Science, University of Pisa. Before joining Leicester, he has been a research associate (2003-2005) at the Dipartimento di Informatica (University of Pisa). Emilio Tuosto's main research interests are in theoretical and applied aspects of complex distributed systems. Recently he has been working on automata- and behavioural type-based models of distributed choreographies, contract-based models of distributed interactions, and their application to software engineering of distributed and concurrent systems.

<br/>
<br/>

### Parameterized Verification with Byzantine Model Checker

[Instructions to download and install the tool](https://github.com/konnov/bymc/blob/master/bymc/doc/forte20.md)
<br/><br/>
Threshold guards are a basic primitive of many fault-tolerant algorithms that
solve the following classical problems of distributed computing: reliable
broadcast, two-phase commit, and consensus. Moreover, threshold guards can be
found in recent Blockchain algorithms such as Tendermint consensus.
Byzantine Model Checker (ByMC) implements several techniques for automatic
verification of threshold-guarded distributed algorithms. These algorithms have
the following features: (1) up to t of processes may crash or behave Byzantine;
(2) the correct processes count messages and progress when they receive
sufficiently many messages, e.g., at least t+1; (3) the number n of processes
in the system is a parameter, as well as t; (4) and the parameters are
restricted by a resilience condition, e.g., n > 3t.  Nowadays these algorithms
are implemented in the distributed systems that involve from hundreds to
thousands of computers. To make sure that these algorithms are still correct
for that scale it is imperative to verify them for all combinations of the
parameters. In this tutorial, we give an overview of the techniques implemented in ByMC.
We demonstrate how to use ByMC for parameterized verification of asynchronous
fault-tolerant distributed algorithms. We show how to apply our techniques in
other contexts, for instance, for verification of randomized algorithms and
verification of synchronous algorithms.
<br/> 
<br/>
*Biography:* Igor Konnov is a senior research scientist at Informal Systems (Austria),
spin-off of Interchain Foundation (Switzerland). He is developing model
checking techniques for parameterized and fault-tolerant distributed
algorithms. Before joining Informal Systems and Interchain Foundation, Igor
Konnov worked as a researcher at Inria Nancy (France) and as a postdoc at TU
Wien (Austria). He received his MSc and PhD in Applied Mathematics and Computer
Science from Lomonosov Moscow State University (Russia) in 2003 and 2009. In
2019, Igor received his Habilitation from TU Wien (Austria).

<br/>
<br/>

### CHOReVOLUTION IDRE: An Integrated Development and Run-time Environment for Automatically Realizing and Executing Distributed Applications.

[Instructions to download and install the tool](https://github.com/chorevolution/discotec-2020-tutorial)
<br/>
<br/>
Since late 70’s, the development of concurrent and distributed systems has been receiving much attention from the research community. Choreographies are a form of distributed composition that model the external interaction of the participant services by specifying peer-to-peer message exchanges from a global perspective. When third-party services are to be composed, obtaining the distributed coordination logic required to enforce the realizability of the specified choreography is a non-trivial and error prone task. Automatic support is then needed. CHOReVOLUTION is a platform for the tool-assisted development and execution of choreography-based applications that leverage the distributed collaboration of services specified through service choreographies. It offers an Integrated Development and Runtime Environment (IDRE) comprising a wizard-aided development environment, a system monitoring console, and a back-end for managing the deployment and execution of the system. The tutorial introduces the fundamentals of service choreographies and the CHOReVOLUTION approach as first. Then the introduction of the approach is followed by hands on exercises, where every attendee takes part in developing sample choreography-based distributed applications by using the CHOReVOLUTION IDRE.
<br/> 
<br/>
*Biography:* Massimo Tivoli and Marco Autili are both associate professors at the Department of Information Engineering, Computer Science, and Mathematics – University of L’Aquila. 
Massimo's research focuses on component adaptation and coordination, connector synthesis, software model elicitation, and choreography synthesis. He received a PhD in computer science from the University of L’Aquila. He is co-author of more than 90 publications in leading international scientific journals and conference proceedings in the software engineering domain. He has been scientific coordinator of the EU H2020 CHOReVOLUTION project, and has been involved in several other international research projects with different leading roles. Massimo is, and has been, in the program committees of several international conferences. 
Marco's research focusses on automated software synthesis for composing complex distributed systems, from system architecture to integration code, from coordination to protocol mediation/adaptation. He also works in modeling and analysis of complex distributed systems, automated synthesis of context-aware (mobile) applications, resource-oriented analysis of adaptable (mobile) applications and formal specification and checking of temporal properties. Recently, he is working on the definition of architectural patterns for creating robust, reliable and efficient microservice-based systems, and on the definition of methods and techniques to transform a monolithic system to a microservice-based one.
The development team of CHOReVOLUTION IDRE includes also Amleto Di Salle and Claudio Pompilio.

<br/>
<br/>

### The Probabilistic Model Checker Storm 


[Instructions to download and install the tool](storm-tutorial)
<br/><br/>
We present the probabilistic model checker Storm.
Storm supports the analysis of discrete- and continuous-time variants of both
Markov chains and Markov decision processes. 
Storm has three major distinguishing features.
It supports multiple input languages for Markov models, including the JANI and
PRISM modeling languages, dynamic fault trees, generalized stochastic Petri nets
and the probabilistic guarded command language.
It has a modular set-up in which solvers and symbolic engines can easily be
exchanged.
Its Python API allows for rapid prototyping by encapsulating Storm’s fast and
scalable algorithms.
Empirical evaluation of Storm within the QComp 2019 competition showed that the
tool is state-of-the-art and performed best with regards to runtime and number
of solved benchmarks. 
In the tutorial we report on the main features of Storm and explain how to
effectively use them.
For more information on Storm we refer to our website
http://www.stormchecker.org/ and our recent paper https://arxiv.org/abs/2002.07080.<br/> 
<br/>
*Biography:* Storm is developed at the Software Modeling and Verification group at RWTH
Aachen University since 2012. The principal developers of Storm are Christian
Hensel, Sebastian Junges, Joost-Pieter Katoen, Tim Quatmann and Matthias Volk.

<br/> 
<br/>

### Kollaps/Thunderstorm: Reproducible Evaluation of Distributed Systems

The systematic evaluation of distributed systems is a very challenging task as experimental results can be affected by a wide range of factors.
In particular, the network and its dynamics, such as sudden changes in latency or available bandwidth have a significant impact on the performance of distributed systems. 
In this tutorial we will do a hands-on demonstration of the capabilities of Kollaps/Thunderstorm, a set of tools that allow to deploy and evaluate unmodified off-the-shelf container applications under a controlled network environment.
By the end of this tutorial, attendants will be able to apply these tools in their systems and, we hope, have a better toolset to evaluate the impact of the network in their systems behavior.<br/>
<br/>
*Biography:* Miguel Matos is an assistant professor at the Engineering School of the University of Lisbon (Instituto Superior Técnico) and a Senior Researcher at INESC-ID.His research interests lie in the area of distributed systems, in the subjects of scalability, performance, correctness and systems evaluation. In particular, he is conducting research in blockchain and related problems,consistency and scalability in large scale databases, systems evaluation under faults and experimental reproducibility. His work has been published in venues such as TPDS, JPDC, Eurosys, IPDPS, Middleware, SRDS and DAIS.
The presented work is the result of joint work between Miguel's team at U. Lisboa, Portugal and researchers from U. of Neuchâtel, Switzerland.

<br/>
<br/>

### Typechecking Java protocols with Mungo/StMungo

This is a tutorial on using Mungo/StMungo, a toolchain based on multiparty session
types and their connection with typestates, for distributed programming in Java.
The first tool, Mungo, statically checks that methods are called in certain
permitted sequences, according to a typestate specification. An
application of this is to communication protocols, since send and
receive methods must be called in sequences that are allowed by the
protocol. Mungo extends Java with an optional typestate definition, which defines
an object protocol as a state machine, specifying the permitted sequences of method calls.
The second tool, StMungo(“Scribble-to-Mungo”) helps with instantiating the typestate
definition for communication protocols, by translating from Scribble and generating
Java skeleton code. The resulting prototype can be further implemented, typechecked
by Mungo to ensure that the implementation follows the protocol, and then compiled
and run as usual.
We give an overview of the key stages of the Mungo/StMungo toolchain, from translating
Scribble local protocol specifications to Java, to Java implementation, to Mungo
typechecking, with examples. We then demonstrate the Scribble, StMungo and Mungo
toolchain by specifying and implementing a domain name server(DNS), as a real-world use case.<br/>
<br/>
*Biography:* Ornela Dardha is an Assistant Professor at the School of Computing Science, University
of Glasgow. She is a Co-Investigator within the UK EPSRC programme grant From Data
Types to Session Types: A Basis for Concurrency and Distribution (ABCD), and a Site
Leader of the European RISE Action Behavioural Application Program Interfaces (BehAPI.
Previously, she was a Postdoctoral Researcher (Jan 2014 - Apr 2018) within the ABCD
project. She obtained my PhD in computing science from the University of Bologna, Italy.
She obtained my BSc (2008) and MSc (2010) in computing science both summa cum laude from
Sapienza University of Rome, Italy.
Simon Gay is a Professor of Computing Science and has been at the University of Glasgow since 2000.
He is the Glasgow PI of the the UK EPSRC programme grant From Data Types to Session Types: A Basis for Concurrency and Distribution (ABCD). He has contributed to the study of session types in pi calculus, in functional languages, and in object-oriented languages; the latter work provides the
foundation for Mungo. Laura Voinea is a Research Associate at the School of Computing Science,
University of Glasgow, working on the ABCD project with Simon Gay and Ornela Dardha. She is finishing up my PhD in Computer Science at same university. 
She has received my BSc and MSc in Computer Science at the University of Glasgow.



