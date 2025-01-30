---
title: Invited
menu_show: true
order: 3
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

Alysson Bessani is a professor of the University of Lisbon Faculty of Sciences, Portugal, and the director of the LASIGE research unit.
He received his Ph.D. in Electrical Engineering from UFSC (Brazil) in 2006, was a visiting professor at Carnegie Mellon University (2010) and a visiting researcher at Microsoft Research Cambridge (2014).

Alysson coordinated/collaborated in 13 international projects and co-authored more than 120 peer-reviewed publications on dependability, security, Byzantine fault tolerance, and cloud storage.
He is also the principal researcher behind the [BFT-SMaRt consensus library](http://bft-smart.github.io/library/) and a co-founder of the [Vawlt dependable & secure cloud storage](https://vawlt.io) startup. More information about him can be found at [http://www.di.fc.ul.pt/~bessani](http://www.di.fc.ul.pt/~bessani).

### [Hélène Coullon](http://helene-coullon.fr/) (IMT Atlantique, France) - DisCoTec-wide
{: .keynote}

![Hélène Coullon](/2025/keynote/HeleneCoullon.png){: .keynote}
More information soon.

### [Omar Inverso](https://www.gssi.it/people/professors/lectures-computer-science/item/1018-inverso-omar) (GSSI, Italy) - [COORDINATION](./coordination)
{: .keynote}

![Omar Inverso](/2025/keynote/OmarInverso.png){: .keynote}

More information soon

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

Tutorial on [EnOSlib](https://sed-rennes.gitlabpages.inria.fr/formations/enoslib-acm-rep-24/intro/).
More information soon.

### [Robbert Krebbers](https://robbertkrebbers.nl/) (Radboud University Nijmegen, The Netherlands) - [COORDINATION](./coordination)
{: .keynote}

![Robbert Krebbers](/2025/keynote/RobbertKrebbers.png){: .keynote}

Tutorial on [Actris](https://iris-project.org/actris/).
More information soon.

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

