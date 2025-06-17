---
title: Coordination Abstracts 
---

## [COORDINATION](coordination)

## 1

**Authors:** Christopher Esterhuyse, Benjamin Lion, Hans-Dieter Hiep and Farhad Arbab. 

**Title:** Formal Foundations for Reowolf: Multi-Party Sessions via Synchronous Protocol Programming

**Abstract:**
The Reowolf project developed connectors as a replacement
of two-party network sockets for multi-party communication in next-generation internet applications. Users control connectors via protocols
in the bespoke protocol description language (PDL), which is based on
synchronous languages such as Reo and Esterel. The novelty lies in the
emphasis on dynamism: users refine protocols throughout their execution.
Weformalisethesemanticsof PDL,distinguishingdual notionsof protocol
behaviour: accepted behaviour is highly (de)compositional and specifies
what communication is allowed, while constructed behaviour arises from
protocol execution and accounts for how execution steps interdepend and
interleave via messages sent and received. Toward machine-checking the
correctness of the connector runtime reference implementation, we specify
the API and correctness criteria of PDL runtime systems.

**pdf:** [pdf](../assets/coordinationpdf/1.pdf)


## 2

**Authors:**  Alessandro Aldini and Claudio Antares Mezzina. 

**Title:**Formalizing Errors in CCS with 3-Valued Logic

**Abstract:**
Concurrent and distributed systems are often prone to failures. Errors in modeling an agent’s behavior can propagate into large
interacting systems with unexpected consequences. In this paper, we
propose a theory for the process algebra CCS enriched with a formal
and explicit representation of errors based on McCarthy’s style three-valued logic, which includes the traditional Boolean values and a third
error value. In this setting, we formally study how the emergence of local errors may or may not result in propagation, as also emphasized in a
real-world case study modeling a distributed microservices architecture.

## 3

**Authors:** Robert Rubbens, Petra van den Bos and Marieke Huisman. 

**Title:** Verified Parameterized Choreographies

**Abstract:**
Choreographies are useful for modelling systems with multiple simultaneously executing and communicating participants, e.g. distributed systems. VeyMont can verify correctness of choreographies and
generate verifiably correct code that implements the choreography. Initially, it supported only fixed sets of participants. However, realistic
systems are often parameterized: they scale according to some parameter N . This paper extends VeyMont with parameterized choreographies,
making VeyMont more usable for realistic case studies. Specifically, we
add parameterized primitives such as participant families and parameterized communication. We encode these primitives using a structured
parallelism primitive from the underlying verifier VerCors, and by using conditionals in the endpoint projection, partially delaying projection
until run time. We illustrate the encoding with a distributed summation
choreography, and prove it correct with VerCors.

## 4

**Authors:** Fabio Gadducci, Carlos Olarte and Frank Valencia. 

**Title:** A Constraint Opinion Model

**Abstract:**
This paper introduces a generalized opinion model that extends the
standard DeGroot model by representing agents’ opinions and influences as soft
constraints rather than single real values. This allows for modeling scenarios beyond the scope of the DeGroot model, such as agents sharing partial information and preferences, engaging in discussions on multiple topics simultaneously,
and representing opinions with different degrees of uncertainty. By considering
soft constraints as influences, the proposed model captures also situations where
agents impose conditions on how others’ opinions are integrated during belief
revision. Finally, the flexibility offered by soft constraints allows us to introduce
a novel polarization measure that takes advantage of this generalized framework.

## 5

**Authors:** Nikolaus Huber, Susanne Graf, Philipp Rümmer and Wang Yi. 

**Title:** MIMOSA: A Language for Asynchronous Implementation of Embedded Systems Software

**Abstract:**
This paper introduces the Mimosa language, a programming
language for the design and implementation of asynchronous reactive systems, describing them as a collection of time-triggered processes which
communicate through FIFO buffers. Syntactically, Mimosa builds upon
the Lustre data-flow language, augmenting it with a new semantics to
allow for the expression of side-effectful computations, and extending it
with an asynchronous coordination layer which orchestrates the communication between processes. A formal semantics is given to both the
process and coordination layer through a textual and graphical rewriting calculus, respectively, and a prototype interpreter for simulation is
provided.

## 6

**Authors:** Antonio Brogi, Roberto Casadei, Nicolas Farabegoli, Stefano Forti and Mirko Viroli. 

**Title:** Declarative Deployment Planning for Green Pulverised Collective Computational Systems

**Abstract:**
To promote non-functional goals (e.g., energy efficiency and
reactivity) in system implementations, multiple strategies can be adopted,
including the partitioning of distributed applications and the smart deployment of the resulting sub-components across the edge-cloud continuum.
Within the aggregate computing approach to collective adaptive systems
engineering (e.g., IoT ecosystems and robot swarms), the pulverisation
model of partitioning and deployment works by splitting the collective
computation into device computation rounds and in turn the device com-
putation round in terms of five components: sensing, actuation, behaviour,
state, and communication components. Previous research has investigated
how different deployments of pulverised systems can provide different
trade-offs involving performance and efficiency, with methodologies and
simulation tools to carry out the comparison. However, there is still no
contribution about the generation or search of effective deployments in
the first place. To address this gap, this work introduces Declarative
Deployment Planning for Pulverised Systems (DePPS), an approach and
toolchain based on simulation and a Prolog-based planner to guide the
search of candidate deployments of pulverised systems. The benefits of the
approach lie in its declarativity, modularity, scalability, and amenability
for continuous reasoning of deployment alternatives. We exercise the
approach with synthetic experiments and find out that we can achieve
“greener” deployments (i.e., with low energy consumption and carbon footprint) while preserving good latencies compared to uniform peer-to-peer
deployments.

## 7

**Authors:**  Giorgio Delzanno, Cosimo Laneve, Arnaud Sangnier and Gianluigi Zavattaro. 

**Title:** Decidability Problems for Micro-Stipula

**Abstract:**
Micro-Stipula is a stateful calculus in which clauses can be
activated either through interactions with the external environment or
by the evaluation of time expressions. Despite the apparent simplicity
of its syntax and operational model, the combination of state evolution,
time reasoning, and nondeterminism gives rise to significant analytical
challenges. In particular, we show that determining whether a clause is
never executed is undecidable. We formally prove that this undecidability result holds even for syntactically restricted fragments: namely, the
time-ahead fragment, where all time expressions are strictly positive, and
the instantaneous fragment, where all time expressions evaluate to zero.
On the other hand, we identify a decidable subfragment: within the instantaneous fragment, reachability becomes decidable when the initial
states of functions and events are disjoint.

## 8

**Authors:**  Carlos Gustavo Lopez Pombo, Agustín Eloy Martinez-Suñé, Hernan Melgratti, Diego Senarruzza Anabia and Emilio Tuosto. 

**Title:** Behavioural, Functional, and Non-Functional Contracts for Dynamic Selection of Services

**Abstract:**
We propose a mechanism for selecting distributed services
which encompasses three orthogonal, yet related type of contracts’ compliance. Indeed, we envisage contract compliance as the intersection of behavioural contract compliance with the compliance of functional and non-functional contracts. We model services as communicating-finite state
machines (CFSMs) suitably extended to capture data-awareness and
application-level quality-of-service (QoS). This extension is instrumental
to define our notion of contract compliance in terms of a bisimulation
relation for this new class of CFSMs. More precisely, we introduce CFSMs where transitions are decorated with constraints on the payloads
while states of CFSMs have decorations that carry QoS contracts. This
allows us to capture behavioural contracts (considering the communication pattern as usual in systems of CFSMs) as well as functional and
non-functional contracts. We use a case study to assess our approach
and we discuss tool support for our framework.

## 9

**Author:**  Carolyn Talcott. 

**Title:**Dialects for the CoAP IoT Messaging Protocol

**Abstract:**
Messaging protocols for resource limited systems such as distributed IoT systems are often vulnerable to attacks due to security
choices made to conserve resources such as time, memory, or bandwidth.
Protocol dialects are a light weight, modular mechanism to provide security guarantees such as authentication or integrity. In this paper we propose a generic dialect for the Constrained Application Protocol (CoAP)
messaging protocol. The CoAP protocol, dialect, and an attack models
are formalized in the rewriting logic system Maude. A number of properties relating CoAP and its dialected form are given, including a stuttering
bisimulation, thus ensuring that dialecting preserves important properties of a CoAP application. The ideas are illustrated with some simple
scenarios.

## 10

**Authors:**  Tilman Zuckmantel, Thomas Hildebrandt, Yongluan Zhou and Boris Düdder. 

**Title:** DACEO: Declarative Asynchronous Choreographies with Data-dependent Event Ordering

**Abstract:**
We provide a formal modeling language, DACEO, for declarative asynchronous choreographies with general data-dependent message
ordering and data objects. The language is equipped with execution semantics, and thereby, it can be used to specify the semantic and support
monitoring of asynchronous distributed event-based systems in which a
total ordering of message delivery cannot be assumed. DACEO models are graphs, which extends previous work on synchronous declarative
choreographies based on Dynamic Condition Response Graphs and their
operational semantics by adding asynchronous message channels with
general data-dependent ordering constraints as well as general objects
and data activities. The addition of objects builds on recent work on
object-centric Dynamic Condition Response Graphs. We show that the
DACEO Graphs can be encoded as the more basic Synchronous Object-centric Dynamic Condition Response Choreographies, preserving the se-
mantics. We motivate DACEO by demonstrating its applicability in describing data-dependent ordering constraints between messages using a
running example that shows how a system with causal consistency requirements can be specified. The marketplace is built on a benchmark for
microservices that relies on asynchronous, event-based communication.



## 11

**Authors:**  José Proença and Maurice H. ter Beek. 

**Title:** RebeCaos

**Abstract:**
We describe RebeCaos, a user-friendly web-based front-end
tool for the Rebeca language, based on the Caos library for Scala. RebeCaos can simulate different operational semantics of (timed) Rebeca, thus
facilitatingthedisseminationandawarenessof Rebeca,providinginsights
into the differences among existing semantics for Rebeca, and supporting
quick experimentation of new Rebeca variants (e.g., when the order of
received messages is preserved). The tool also comes with initial reachability analyses for Rebeca models (e.g., the possibility of reaching dead-
locks or desirable states). We illustrate the RebeCaos tool by means of a
ticket service use case from the timed Rebeca literature.


## 12

**Authors:**  Gianluca Aguzzi, Lorenzo Bacchini, Martina Baiardi, Roberto Casadei, Angela Cortecchia, Davide Domini, Nicolas Farabegoli, Danilo Pianini and Mirko Viroli. 

**Title:** A Demonstrator Toolchain for Self-organizing Robot Teams

**Abstract:**
Aggregate computing is a paradigm with over a decade of
investigation and multiple programming frameworks available, which
proved to be particularly suitable for the simulation of applications in
challenging domains such as smart cities and robot swarms. This paper
introduces a toolchain for practical multi-robot demonstrations based on
aggregate computing principles, and validates it with a live interactive
demo in an open-public event in the context of the European Researchers’
Night. More specifically, we show how we coordinated a team of mobile
robots to form spatial patterns. We discuss the practical demonstration
performed in an indoor environment, which exploits a camera system
and ArUco markers for localization.

