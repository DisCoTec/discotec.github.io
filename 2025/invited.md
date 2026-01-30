---
title: Invited
menu_show: true
order: 3
year: 2025
---

# Invited Speakers

DisCoTec 2025 has invited speakers to give [keynote talks](#keynote-talks) and [tutorials](#tutorials).

## Keynote Talks

DisCoTec 2025 will host a keynote talk at each conference as well as a DisCoTec-wide keynote.
The invited speakers are
[Alysson Bessani](#alysson-bessani-universidade-de-lisboa-portugal---dais) ([DAIS](./dais)), [Hélène Coullon](#hélène-coullon-imt-atlantique-france---discotec-wide) (DisCoTec-wide), [Omar Inverso](#omar-inverso-gssi-italy---coordination) ([COORDINATION](./coordination)), and [Burcu Ozkan](#burcu-ozkan-tu-delft-the-netherlands---forte) ([FORTE](./forte)).

### [Alysson Bessani](https://ciencias.ulisboa.pt/en/perfil/anbessani) (Universidade de Lisboa, Portugal) - [DAIS](./dais)
{: .keynote}

![Alysson Bessani](/2025/keynote/AlyssonBessani.png){: .keynote}

**Title:** _The Power of Simplicity on Dependable Distributed Systems_

**Abstract:** Contrary to a (somewhat) common belief, the most important property of a practical distributed algorithm is not its efficiency or performance but its simplicity. This fact is even more evident when considering dependable distributed systems. In this talk, I will present some cases in which simple protocols and elegant abstractions - which were not the most efficient for the problem at hand - enabled the deployment of dependable solutions that changed the practice of distributed computing. I will also discuss how the quest for simplicity influenced my work on Byzantine fault tolerance and cloud storage. Ultimately, I aim to convince the audience that "simplicity is the ultimate sophistication" in distributed computing.

**Bio:** Alysson Bessani is a professor of the University of Lisbon Faculty of Sciences, Portugal, and the director of the LASIGE research unit.
He received his Ph.D. in Electrical Engineering from UFSC (Brazil) in 2006, was a visiting professor at Carnegie Mellon University (2010) and a visiting researcher at Microsoft Research Cambridge (2014).

Alysson coordinated/collaborated in 13 international projects and co-authored more than 120 peer-reviewed publications on dependability, security, Byzantine fault tolerance, and cloud storage.
He is also the principal researcher behind the [BFT-SMaRt consensus library](http://bft-smart.github.io/library/) and a co-founder of the [Vawlt dependable & secure cloud storage](https://vawlt.io) startup. More information about him can be found at [http://www.di.fc.ul.pt/~bessani](http://www.di.fc.ul.pt/~bessani).

### [Hélène Coullon](http://helene-coullon.fr/) (IMT Atlantique, France) - DisCoTec-wide
{: .keynote}

![Hélène Coullon](/2025/keynote/HeleneCoullon.png){: .keynote}

**Title:** _Challenges in Infrastructure-as-Code: efficiency, decentralization, and formalization_

**Abstract:** In this talk I will try to draw your attention to infrastructure-as-code (IaC) tools and languages. These languages enable managing distributed infrastructures and applications through code, thus achieving interesting properties such as versionability, testability, and sharability. Their use is particularly crucial for automatically and correctly managing resources in the Cloud, especially for large-scale infrastructures (fog or edge computing). Infrastructure-as-Code languages include aspects of programming languages, life-cycle coordination, dynamic reconfiguration and autonomic computing. I am going to focus in particular on three scientific challenges in IaC: efficiency, decentralization and formalization.

This talk will be punctuated by my own contributions to dynamic reconfiguration:
a full study to leverage programmable life-cycles of software entities and their automatic coordination during reconfigurations. This programmability offers more opportunities for parallelism and concurrency. As a consequence, programmable life-cycles significantly reduce the execution time of reconfigurations. However, as more complexity is introduced, it becomes harder to guarantee other positive properties offered by the literature: safety, declarativity, and decentralization.

I will open this talk on the problem of resilience and robustness of infrastructure and associated potential new challenges in IaC.

**Bio:** Hélène Coullon is an associate professor at IMT Atlantique, France. She received her Ph.D. in 2014 from the University of Orléans (France). Her research topics are large-scale distributed and geo-distributed systems, in particular their deployment and dynamic reconfiguration.
She combines expertise from different fields including Component-Based Software Engineering (CBSE), Infrastructure-as-Code (IaC), formal methods and languages, parallelism, and domain specific languages.


### [Omar Inverso](https://www.gssi.it/people/professors/lectures-computer-science/item/1018-inverso-omar) (GSSI, Italy) - [COORDINATION](./coordination)
{: .keynote}

![Omar Inverso](/2025/keynote/OmarInverso.png){: .keynote}

**Title:** _Towards Automated Analysis of Emerging Behaviour: Preliminary Insights and Research Directions_

**Abstract:** In several classes of collective systems, sophisticated dynamics may occur for the combined effect of the elementary actions of the individuals. For instance, foraging ants in a colony are able to collectively work out the most convenient path while carrying food back to their nest. Somehow similarly, unintended order may arise spontaneously among the involved parties of some economic systems.

Fascinating phenomena of this kind are studied in a variety of disciplines, from biology to physics, where the main challenge is to understand the relationship between the way individuals behave in isolation and what happens over time at a global level in the system.

This talk summarises a few proofs of concept on the automated analysis of different systems, such as stable matchings, flocks of birds, colonies of ants, and applauding audiences, and relevant emerging properties thereof. The underlying methodology follows an integrated approach to formal specification and analysis to leverage intuitive specification languages as well as existing mature verification technology and decision procedures for general-purpose applications.

**Bio:** Omar Inverso is an associate professor at the Gran Sasso Science Institute in L'Aquila, Italy. His research interests include formal languages and methods, automated analysis, and decision procedures, with applications to concurrent and distributed systems, and so-called collective or complex systems at large.

### [Burcu Kulahcioglu Ozkan](https://burcuku.github.io/home/) (TU Delft, The Netherlands) - [FORTE](./forte)
{: .keynote}

![Burcu Kulahcioglu Ozkan](/2025/keynote/BurcuOzkan.png){: .keynote}

**Title:** _From Formal Methods to Testing of Distributed Systems_

**Abstract:** Distributed systems are prone to software bugs due to the concurrency of distributed events and potential network and process faults during execution. Detecting these bugs is notoriously challenging because they often occur only in specific, subtle interleavings of the events.  In principle, these bugs could be detected by model-checking techniques, which explore all possible event schedules. However, systematic exploration does not scale to large distributed systems, and it is only practical to test a subset of their executions. Alternatively, randomized testing is a practical method to apply to large systems, but it comes with limitations in its effectiveness.

Our recent works narrow the gap between formal verification and randomized testing of distributed systems, bringing together the effectiveness of formal methods and the practicality of randomized testing. In this talk, we will overview the key ideas in our recent works and discuss how transferring ideas from formal methods and verification improves the effectiveness of randomized test generation.

**Bio:** Burcu Kulahcioglu Ozkan is an assistant professor and Delft Technology Fellow in the Software Engineering Research Group at TU Delft. She received her PhD from Koç University in Istanbul, Turkey, followed by postdoctoral research at the Max Planck Institute for Software Systems (MPI-SWS) in Kaiserslautern, Germany. Her research focuses on formal methods, model checking, software testing, and debugging of concurrent programs and distributed systems. She is a recipient of the academic research awards and grants from Amazon Research and Stellar Development Foundation.

## Tutorials

DisCoTec 2025 will host a tutorial at each conference.
The invited speakers are
[Baptiste Jonglez](#baptiste-jonglez-inria-france---dais) ([DAIS](./dais)), [Robbert Krebbers](#robbert-krebbers-radboud-university-nijmegen-the-netherlands---coordination) ([COORDINATION](./coordination)), and [Emilio Tuosto](#emilio-tuosto-gssi-italy---forte) ([FORTE](./forte)).

### [Baptiste Jonglez](https://stack-research-group.gitlabpages.inria.fr/web/pages/members.html) (Inria, France) - [DAIS](./dais)
{: .keynote}

![Baptiste Jonglez](/2025/keynote/BaptisteJonglez.png){: .keynote}

**Title:** _Driving distributed system experiments on the edge-to-cloud continuum with EnOSlib_

**Abstract:** 
[EnOSlib](https://discovery.gitlabpages.inria.fr/enoslib/index.html) is a Python library that facilitates the design and execution of
reproducible experiments across distributed computing
infrastructures. Originally developed to simplify experimentation on
testbeds such as Grid’5000 and Chameleon Cloud, its scope is expanding to
include edge testbeds. In addition, edge-to-cloud experiments are
facilitated thanks to a new feature: EnOSlib now supports multi-provider
deployments, allowing simultaneous resource reservation and deployment
across several diverse testbeds at the same time.

EnOSlib also provides reusable services, for example fine-grained energy
measurements, automated Kubernetes cluster deployments, classical
monitoring stacks, or enhanced network emulation.  All these features enable
users to model and study complex, realistic scenarios such as
latency-sensitive edge-to-cloud applications.

The tutorial illustrates these capabilities through a distributed video
processing use-case that spans edge and cloud platforms.

### [Robbert Krebbers](https://robbertkrebbers.nl/) (Radboud University Nijmegen, The Netherlands) - [COORDINATION](./coordination)
{: .keynote}

![Robbert Krebbers](/2025/keynote/RobbertKrebbers.png){: .keynote}

**Title:** _Mechanized Type Soundness for Substructural Types using Iris_

**Abstract:**
Substructural type systems are a good fit to enforce strong safety properties of higher-order, imperative and concurrent programs. Key examples are the Rust type system (which enforces the absence of undefined behavior and data races) and session types (which enforce correct usage of message-passing channels). Formally proving that these type systems "do their job" (i.e., they enjoy the "type soundness" property) is challenging. This challenge is exacerbated when considering combinations of language features ("feature interaction") and linking against "unsafe" libraries (which have to be verified manually), thus providing the desire for a scalable approach with support for machine-checked proofs.

In this tutorial I will give an introduction to the "logical approach" to type soundness, which is well-suited to prove soundness of substructural type systems. I will explain the theory of the logical approach in the context of a very simple language, which I then gradually scale up to a session-typed language. I will also demonstrate that the logical approach is well-suited for the mechanization of challenging type systems in the Rocq proof assistant using the Iris framework for concurrent separation logic.

### [Emilio Tuosto](https://cs.gssi.it/emilio.tuosto/) (GSSI, Italy) - [FORTE](./forte)
{: .keynote}

![Emilio Tuosto](/2025/keynote/EmilioTuosto.png){: .keynote}

**Title:** _A choreographic view of Smart Contracts_ 

Joint work with Elvis Konjoh Selabi (UniCam and GSSI), Maurizio Murgia
(GSSI), and António Ravara (NOVA, Lisbon). 

**Abstract:**
We recently proposed a coordination model that blends together ideas
from smart contracts, choreographies, and typestates to formalise and
reason about interactions of distributed components. Our framework is
based on symbolic finite-state machines dubbed DAFSMs (after
Data-Aware Finite-State Machines) to
holistically capture *coordination protocols* which, akin smart
contracts, expose an API that distributed components use to interact
according to the *role* they play in the protocol. As global
specifications such as global types, DAFSMs allow us to define so-called
*well-formedness* properties, while abstracting away from run-time
details such as the number of number of components' instances enacting
the roles of the protocol. Interestingly DAFSMs can represent
data-dependency. This is a quintessential aspect to handle properties
that, like well-formedness, depend on the payloads of components'
interactions such as those typical in smart contracts.

The tutorial will show how to use DAFSMs to formalise coordination
protocols and analyse their well-formedness using a Tool for
Resource-Aware Coordination ([TRAC](https://github.com/loctet/TRAC)),
designed to support our approach.

