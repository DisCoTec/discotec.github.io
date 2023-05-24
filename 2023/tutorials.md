[![](https://www.discotec.org/2023/discotec2023-banner.jpeg)](https://www.discotec.org/2023/)

# Tutorials

The DisCoTec Tutorials focus on emerging topics and aspects of the distributed computing field, ranging from new practical techniques and technologies to lessons learnt from projects and industry experiences.

## Implementing and Evaluating Distributed Protocols with Babel.

### Description

In this tutorial we guide the audience through the implementation and evaluation of a simple distributed application with a tool that simplifies this process: Babel. Implementing and evaluating distributed applications and protocols is a dificult task. The developer must focus on many aspects of the implementations that include: networking, concurrency control, the handling of timeouts, the interaction between components, among others. Babel [2] is a tool and framework that simplifies the task of developing distributed applications and protocols by allowing the developer to focus mostly on the application/protocol logic. Babel achieves this by providing high level APIs that shield the developer from error-prone implementation aspects, mainly networking and concurrency control. The goal of the tutorial is to familiarize the audience with Babel by implementing a simple distributed application constituted by two protocols that interact with each other.  Furthermore, we will also provide a simple way to evaluate the implementations through emulation.

### Speakers

#### Pedro Fouto

Pedro Fouto is a Computer Science PhD student advised by Professors João Leitão and Nuno Preguiçaa at NOVA University of Lisbon. His main research area is distributed storage systems, where he has used Babel to develop his prototypes. In more detail, Babel was used to develop the prototypes presented in the paper "High Throughput Replication with Integrated Membership Management" published in the Proceedings of USENIX ATC'22. Pedro Fouto is also the first author of the Babel paper.

#### Pedro Santos Costa
Pedro Santos Costa is a Computer Science PhD student advised by Professor João Leitão at NOVA University of Lisbon.  His main research is distributed systems, where he has used Babel to develop the prototypes used in the paper "Overlay networks for edge management" published in the Proceedings of NCA'20. Pedro Santos Costa is also a co-author of the Babel paper.

#### João Leitão
João Leitão is an Associate Professor at the Department of Computer Science of the NOVA University of Lisbon. João Leitão teaches an advanced distributed systems courses where the students employ Babel to develop their project. João Leitão is also one of the authors of the Babel paper, published in 2022 in the Proceedings of SRDS'22.

---

## Deductive Verification of OCaml Programs in Cameleer.

In this tutorial we present Cameleer, an automated deductive verification
tool for OCaml. We leverage on the recently proposed GOSPEL (Generic
OCaml SPEcification Language) to attach rigorous, yet readable, behavioral specification to OCaml code. 
The formally-specified program is fed to our toolchain, which translates it into an equivalent one in WhyML,
the programming and specification language of the Why3 verification
framework.  The tutorial is mainly an hands-on introduction to the tool and the verification of OCaml programs, 
annotated with GOSPEL specification elements. The following five case studies are used during the tutorial:

- XOR-based cipher [.ml]
- A simple applicative data structure, based on forests [.ml]
- Array scanning function, using a for-loop [.ml]
- Ephemeral implementation of a FIFO data structure [.ml]
- Leftist Heaps implementation, directly issued from the ocaml-containers library [.ml]

### Speaker
#### Mário Pereira

[Mário Pereira](https://mariojppereira.github.io/) is Assistant Professor at NOVA School of Science and Technology, as well as an integrated member of NOVA LINCS. Prior, he held a Marie Skłodowska-Curie individual fellowship (March 2020 - May 2022), where he was the main architect and lead developer of Cameleer, a framework for the deductive verification of OCaml-written code. Pereira completed his PhD in 2018, under the supervision of Jean-Christophe Filliâtre at Université Paris-Saclay. He is an expert in deductive software verification and functional programming. He actively collaborates with worldwide-acknowledged lead researchers in the fields of functional programming and software verification, namely in the development of the GOSPEL specification language and the Why3 verification framework.
 

---

## SeTTS: Session Type Test Synthesis for Web-based APIs.

### Description

 Most computer applications consist of software components that  interact by exchanging messages across a network. Such messages often  depend on each other and must follow a certain order, based on how  they change the state of the application. This is the case for many  classic Internet protocols (e.g., SMTP, IMAP, etc.); also, modern  web-based APIs (e.g. REST, GraphQL, etc.) have implicit dependencies  where some messages (i.e., HTTP requests) may enable/disable further  operations and resources. Testing these message-passing applications  typically requires a substantial amount of handwritten code. Previous
 work has explored the automatic, randomised generation of tests for  REST APIs, which can speed up the testing process, but it offers  limited support for testing non-trivial sequences of interdependent  requests.

 In this tutorial, we present an approach to test message-passing  applications — with an emphasis on REST APIs. We model  message-passing protocols using session types, and present a DSL based on OpenAPI specifications to specify the shape of correct message exchanges or API usages. This approach is instantiated in a tool, SeTTS, that generates randomised test executions and reports if the system under test violates the specification. We will showcase the usability of the tool on several open-source applications and show that it achieves comparable coverage w.r.t. handwritten tests, while only requiring a fraction of their code.

### Speaker
#### Christian Bartolo Burlo 

 Christian Bartolo Burlo (https://github.com/chrisbartoloburlo) is a PhD student in Computer Science at the Gran Sasso Science Institute. His research activity concerns the development of tools and techniques for the verification of interacting software, backed by a formal foundation.
 
---

## Local-First Principles: a Behavioural Typing Approach.

### Description

Fully distributed systems where components coordinate merely by exchanging messages are notoriously difficult to realise. A source of complexity is that maintaining invariants of the computation is hard: on the one hand, such invariants are properties of the *global* state emerging from the *local* states of the components; on the other hand, design principles suggest avoiding centralisation points in order to reduce bottlenecks and increase scalability and robustness. Therefore, distributed components have to coordinate with each other in order to maintain invariants. This boils down to ensure correct information flows through components.

A radically new approach is to trade consistency for availability in the design of distributed systems advocating ideas from *local-first software*: components should operate no matter how precisely their “local view reflects the global computational state”...Hence, inconsistent states will obviously emerge! But the local-first philosophy is to embrace the emergence of local inconsistencies provided that global consistency is eventually attained. These ideas are the bread & butter of the [Actyx's platform](https://developer.actyx.com), an industrial middleware to coordinate applications consisting of *local-twins*, that is computational agents that do not rely on any central components such as servers, databases, or cloud.

This tutorial will discuss the distributed coordination of communicating systems based on local-first principles, present a formal model capturing the semantics of the Actyx platform, and then present an approach based on a new class of behavioural types to specify and analyse systems consisting of distributed components communicating through an event notification mechanism. This formal framework has been implemented in a prototype demonstrated in the tutorial.  The tutorial is based on joint work with Roland Kuhn (Actyx AG, Germany) and Hernán Melgratti (UBA & CONICET, Argentina)


### Speaker

#### Emilio Tuosto
Emilio Tuosto is an associate professor at the [Gran Sasso Science Institute](http://www.gssi.it).  Emilio's main research interests are in theoretical and applied aspects of distributed and mobile systems. Recently he has been working on automata- and type-based models of distributed choreographies, contract- and graph-based models of distributed interactions.

Before joining the GSSI, Emilio has been associate professor of the [School of Informatics](https://cs.le.ac.uk/) of [University of Leicester](https://www.le.ac.uk), which he joined in October 2005 as a lecturer of the Department of Computer Science. Emilio has been a research associate (2003-2005) at the Dipartimento di Informatica (University of Pisa). He graduated (1998) and got his PhD degree in Computer Science (2003) at the department of Computer Science, University of Pisa.

---

## JaTyC - Java Typestate Checker

### Description

[JaTyC](https://github.com/jdmota/java-typestate-checker) is a tool that verifies Java source code with respect to *typestates*. A typestate is associated with a Java class with the `@Typestate` annotation and defines: the object's states, the methods that can be safely called in each state, and the states resulting from the calls. The tool statically verifies that when a Java program runs: sequences of method calls obey to object's protocols; objects' protocols are completed; null-pointer exceptions are not raised; subclasses' instances respect the protocol of their superclasses.

JaTyC is a plugin for the [Checker Framework](https://checkerframework.org/). It is a purely transparent checker, i.e. does not modify the baseline Java compilation. This tool was inspired in the [Mungo](https://www.dcs.gla.ac.uk/research/mungo/) toolset. It is a new implementation that includes new features and improvements over the current version of Mungo. A comparison table between Mungo and this tool is available [here](https://github.com/jdmota/java-typestate-checker/wiki/Mungo-comparison). Features include:

- checking that methods are called in the correct order specified by the protocol;
- checking that protocols of objects are completed;
- checking the absence of null pointer errors;
- support for protocols to be associated with classes from the standard Java library or from third-party libraries;
- support for "droppable" states, which allow one to specify states in which an object may be "dropped" (i.e. stop being used) without having to reach the final state;
- support for transitions of state to depend on boolean values or enumeration values returned by methods.

Invalid sequences of method calls are also ignored when analysing the use of objects stored inside other objects by taking into account that the methods of the outer object will only be called in the order specified by the corresponding protocol, thus avoiding false positives.

It is worth noticing that JaTyC provides support for subtyping: a class with a protocol may extend another class with another protocol and the tool will ensure that the first protocol is a subtype of the second protocol.
One can also create a class with a protocol that extends a class without protocol. In the class without protocol, all methods are available to be called and remain so in the subclass. Then in the subclass, one can add new methods and restrict their use by only allowing them in certain states.

### Speakers

#### João Mota

[João Mota](https://github.com/jdmota/) is a PhD student at the [Department of Computer Science](https://www.di.fct.unl.pt/en) of the [NOVA School of Science and Technology](https://www.fct.unl.pt/en). The problem João is tackling is integrating object sharing mechanisms with typestates in a concurrent object-oriented language that statically guarantees safety properties: protocol compliance, protocol completion, and absence of data-races. For his MSc dissertation, João developed JaTyC, a tool that verifies Java source code with respect to typestates.

#### Marco Giunti

[Marco Giunti](http://ctp.di.fct.unl.pt/~mgiunti/) is a senior researcher associated with [NOVA LINCS](https://nova-lincs.di.fct.unl.pt/). 
His research interests span the areas of behavioral type systems and static analysis, computer-assisted proofs, functional programming, language-based security, and process algebraic models of concurrent computations. He believes in static analysis techniques that are formally verified by means of proof assistants, and uses Coq to mechanise type and inference systems for mobile and object-oriented core languages. 

#### António Ravara

[António Ravara](https://nova-lincs.di.fct.unl.pt/people/antonio-ravara#resume) is an Associate Professor at the [Department of Computer Science](https://www.di.fct.unl.pt/en) of the [NOVA School of Science and Technology](https://www.fct.unl.pt/en). The main research problem driving António's work is how to ensure that inherently concurrent, highly distributed, software systems behave correctly. The focus is on the development of techniques, program constructions, and tools that help create safe and well-behaved systems, provably providing correctness guarantees. The toolbox used includes static analysis of source code, capturing defects before deployment, with decidable, low complexity, property-driven, proof systems, using behavioural descriptions of programs.

#### Mário Bravetti

[Mario Bravetti](https://www.unibo.it/sitoweb/mario.bravetti/en) is a Full Professor at the [Computer Science and Engineering Department of University of Bologna](https://disi.unibo.it/en). He is also permanent member of the [FOCUS (Fundations of Component-based Ubiquitous Systems)](https://team.inria.fr/focus/) team which is part of the INRIA Sophia Antipolis - Méditerranée French research center. He is PhD in computer science and winner of the award for the two best Italian PhD theses in theoretical computer science in the year 2002, assigned by the Italian Chapter of the European Association for Theoretical Computer Science. His research activity spans from formal description and verification of distributed systems based on concurrency and probability theory to more applicative topics such as service oriented and cloud computing.

#### Lorenzo Bacchiani

[Lorenzo Bacchiani](lorenzo.bacchiani@unibo.it) got his M.Sc. degree in Computer Science at the University of Bologna in 2020. 
He is now a Ph.D. student in Computer Science and Engineering in the same university. He is currently working on behavioral based approaches and languages for component interaction, adaptation and deployment.

