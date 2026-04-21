---
title: Invited
menu_show: true
order: 1
year: 2026
---

# Invited Speakers

DisCoTec 2026 has invited speakers to give [keynote talks](#keynote-talks) and [tutorials](#tutorials).

## Keynote Talks

DisCoTec 2026 will host a keynote talk at each conference as well as a DisCoTec-wide keynote.
The invited speakers are
[Mehdi Dastani](#mehdi-dastani-coordination) ([COORDINATION](./coordination)), [Paolo Romano](#paolo-romano-dais) ([DAIS](./Dais)), [Nathalie Bertrand ](#natalie-bertrand-forte) ([FORTE](./forte)), and [Roberto Bruni](#broberto-bruni-university-of-pisa---discotec-wide) (DisCoTec-wide).


### [Roberto Bruni](https://pages.di.unipi.it/bruni/) (University of Pisa, Italy) - DisCoTec-wide
{: .keynote}


**Title:** _A logic for all reasons_

**Abstract:** Program verification draws on a rich spectrum of program logics, each
offering a distinct perspective on program behaviour. Hoare Logic deals
with proving the absence of bugs (i.e., partial correctness) through
over-approximations of reachable states. Incorrectness Logic, in
contrast, identifies reachable error states without false alarms and
Lisbon triples pinpoint concrete sources of errors with the same
guarantee. Necessary condition logic and predicate transformers further
enrich this landscape.

Despite their individual strengths, these frameworks are typically
developed and applied in isolation, limiting their potential to improve
precision and strengthen static analysis guarantees. In verification, as
elsewhere, union is strength: integrating orthogonal reasoning
principles enables analyses that are strictly more expressive and
informative than before.

In this talk, we propose a unifying framework that systematically
combines multiple analysis dimensions: direction (forward and backward)
and approximation (under-, exact, and over-approximation), all within a
simple lattice of program triples. By elevating approximation modes to
first-class objects, we lay a principled foundation for modular,
compositional, and expressive reasoning. Our approach reconciles
correctness and incorrectness within a single logical framework,
enabling the derivation of code summaries that can inhabit any point in
the program logic landscape.

**Bio:** Roberto Bruni is Full Professor at the Computer Science Department of
the University of Pisa.
His research focuses on the modeling, analysis, and verification of
concurrent, distributed, adaptive, and open systems, as well as on
natural computing and bio-inspired models of computation. He has
contributed to a wide range of areas including Petri nets, rewriting
logic, category theory, process algebras, service-oriented computing,
multiparty interactions, Reaction Systems, abstract interpretation and
program logics. He has co-authored over 170 publications, including
textbooks and monographs, and has been actively involved in numerous
international research projects and the organization of international
conferences. He received his PhD in Computer Science from the University
of Pisa.

### [Mehdi Dastani](https://www.uu.nl/staff/MMDastani) (Utrecht University, The Netherlands) - COORDINATION
{: .keynote}
**Title**: _Efficient Communication and Coordination in Multiagent Reinforcement Learning_  

**Abstract**: Multiagent reinforcement learning (MARL) is a powerful framework for learning effective policies in complex multiagent environments. A key challenge in MARL is to learn coordinated policies efficiently in a decentralised manner. Prior work has explored a range of communication and coordination mechanisms to address these challenges. 

In this talk, I will present our recent contributions towards improving the efficiency and performance of MARL systems through principled communication and coordination mechanisms. First, I introduce a decentralised communication scheduling approach that leverages supervised learning to construct a message estimation model. This model enables individual agents to selectively decide when sharing local information is beneficial, thereby reducing unnecessary communication. Empirical results show that this approach significantly decreases communication overhead while improving overall learning performance. Second, I present two logic-based methods for synthesising multiagent reward machines and action-masking artefacts. These methods provide formal guarantees that the resulting policies are both coordinated and safe, while also improving sample efficiency. 


### [Paolo Romano](https://www.dpss.inesc-id.pt/~romanop/) (INESC-ID Lisbon - Distributed Systems Group, Portugal) - DAIS

**Title**: Processing-in-Memory for Next-Generation Data Pipelines: From OLTP to AI Feature Stores

**Abstract**:

Processing in Memory (PIM) architectures, exemplified by the first commercially available UPMEM platform, bring lightweight Data Processing Units (DPUs) directly into DRAM modules. This approach dramatically reduces data movement, which is the dominant bottleneck in many modern data intensive workloads. In this talk I will present our journey from the first software transactional memory (STM) layer for PIM to the first cross-DPU OLTP engine, and our most recent work on leveraging PIM to accelerate feature stores for the inference phase of AI applications.

I will start by presenting PIM STM [1], a family of STM implementations tailored to UPMEMs unique hardware constraints (limited WRAM MRAM tiers, weak atomic primitives, and no direct inter DPU communication). Via an extensive study we have systematically assessed the efficiency of key choices in the concurrency control  design space for this emerging architecture, as well as quantified the impact of using different memory tiers of the UP-MEM system to maintain transactional metadata.

I will then introduce PIM-TIDE, the first PIM-native in-memory transactional store that builds on PIM STM  supports full ACID transactions spanning thousands of DPUs. PIM-TIDE combines deterministic ordering for distributed sub-transactions (pre-computed on the host) with lightweight non-deterministic STM for local transactions, eliminating expensive distributed  transaction coordination protocols and CPU-mediated inter-DPU messaging. On OLTP workloads, PIM-TIDE achieves up to 6.75× higher throughput and 3.52× better energy efficiency than a 52-core CPU baseline, demonstrating that PIM can deliver both performance and sustainability gains for classic OLTP.
Finally, I will present our ongoing work on PIM, which aims at accelerating feature stores, namely  the data-preparation backbone of ML inference pipelines. Feature computation (such as rolling aggregates and joins) is memory-bound, exhibits massive parallelism, and often needs to comply with strict latency requirements, e.g.,  in the fraud detection domain. By offloading feature computation kernels to DPUs,  I will show that it is possible to achieve order-of-magnitude speed-ups and energy reductions, but that it is crucial to integrate solutions capable of effectively dealing with data skew and of taking maximum advantage of the memory hierarchy within a DPU.

**Bio**:

Paolo Romano received his PhD from Rome University "Sapienza" (2007) and his Master degree summa cum laude from Rome University"Tor Vergata" (2002). He is currently an associate professor at Lisbon University, Portugal and a researcher at INESC-ID. 

His research is focused on parallel and distributed systems, with a strong emphasis on leveraging emerging hardware technologies —including Processing-In-Memory, Persistent Memory and Transactional Memory — to achieve high efficiency, performance, and dependability. He leads work on concurrency control for PIM systems, heterogeneous computing, persistent memory, and energy-efficient data management. These efforts aim to overcome traditional memory bottlenecks, reduce data movement, and enhance throughput and memory efficiency for AI/ML systems, transactional applications, and high-performance computing.

In these areas, he published more than 200 papers, receiving 5 best paper awards, and has coordinated several national and European projects, including a COST Action bringing together researchers from 60 institutions and 17 countries. He serves regularly as Program Committee member and reviewer for renowned international conferences and journals, including EuroSys, DSN, ICDCS, PPoPP, IEEE TKDE, IEEE TPDS, ACM TOPLAS. 


