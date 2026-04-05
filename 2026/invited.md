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
