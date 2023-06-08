[![](discotec2023-banner.v3.png)](https://www.discotec.org/2023/)

# DisCoTec 2023 Invited Speakers

## Azalea Raad

[Imperial College London, UK](https://www.soundandcomplete.org/)  

###  Principles of Persistent Programming

Persistent programming is the art of developing programs that operate on persistent (non-volatile) states that survive program termination, be it planned or abrupt (e.g. due to a power failure). Persistent programming poses several important challenges: 1) persistent systems have complex—and often unspecified—semantics in that operations do not generally persist in their execution order; 2) software bugs in persistent settings can lead to permanent data corruption; and 3) traditional testing techniques are inapplicable in persistent settings. Can formal methods come to the rescue?


## Frank Pfenning
[Carnegie Mellon University, USA](https://www.cs.cmu.edu/~fp/)

### Relating Message Passing and Shared Memory, Proof-Theoretically

At first sight, message passing concurrency is quite different from shared memory concurrency. Then we remember the well-known encoding of shared memory cells in the π-calculus and also implementations of message passing abstractions using shared memory. Such mutual encodings are significant, but far from straightforward and difficult to reason about rigorously.
We exhibit a strong bisimulation between asynchronous message passing concurrency with session types and shared memory concurrency with futures. A key observation is that both arise from closely related interpretations of the semi-axiomatic sequent calculus with recursive definitions, which provides a unifying framework. As a further result we show that the bisimulation applies to both linear and nonlinear versions of the two languages.

## Peter Pietzuch
[Imperial College London, UK](https://www.doc.ic.ac.uk/~prp/)

### Making Cloud Applications Safe and Efficient with Memory Capabilities

An increasing number of distribution applications, e.g., micro-service architectures and machine learning workloads, are deployed in the cloud. Traditional cloud security focusses on strict isolation, but distributed applications require the efficient yet secure sharing of data between components and services. In this talk, I will explore how we can use a new hardware feature, memory capabilities, to design a cloud stack that bridges the tension between isolation and sharing. Memory capabilities constrain memory accesses, and they can be used to provide a VM-like isolation mechanism, cVMs, that can share data more efficiently than containers. They can also increase efficiency by safely de-duplicating application components. I will discuss our experience in building a cloud stack using memory capabilities on the CHERI architecture, as implemented by Arm's Morello hardware.
