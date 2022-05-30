[![](https://www.discotec.org/2022/discotec2022-banner.jpeg)](https://www.discotec.org/2022/)

# First Workshop on Blockchain Technologies and Trusted Execution Environments


**COVID-19:** BlockTEE'22 is planned as a physical, in-person event, with certain support for remote presence, both for speakers and for other participants who are unable or unwilling to come. Depending on the 
pandemic situation, we may have to make a decision whether to cancel the physical component of the event or not.


# Scope

Blockchains and Trusted Execution Environments (TEE) are popular emerging technologies, enabling new or existing use cases to be deployed under stronger security and trust models. Blockchains and TEEs have been combined in the past to enhance the performance, security and applicability for blockchains. In this workshop, we invite novel combinations of these two technologies. Some of the topics of interest include, but are not limited to:
* practical results that show how to combine these two technologies to operate under stricter security models, 
* offering new performance results, 
* new proof-of-* systems enabled by TEEs, 
* improvements over state-of-the-art ledgers exploiting TEEs, 
* mixed or hybrid TEE deployments for distributed ledgers, 
* novel partitioning techniques dealing with heterogeneous TEE setups for blockchains
* real-world results from large-scale deployments combining TEEs and blockchains are highly encouraged.

# Submission

The first page must contain (1) title, (2) author names and affiliations, (3) contact author’s email, (4) abstract, and (5) indication of whether the paper is a full paper or a position paper as detailed below:

- a position paper should aim at fostering discussion and collaboration and may summarize research published elsewhere or outline emerging ideas. The submission must not exceed 4 pages excluding references. 
- full papers, presenting fleshed out ideas, systems and or experimental results. The submission must not exceed 12 pages excluding references.  


Contributions should be submitted electronically as PDF, using the Springer LNCS style to the conference submission website (https://easychair.org/my/conference?conf=blocktee22). Each paper will undergo a thorough process of peer reviews by the Program Committee. 
Reviewing is single-blind: author name(s) should appear. 


We will have an *hybrid publication model*.
In the spirit of a workshop, the aim of this hybrid model is to facilitate the exchange of ideas and experiences via presentations of preliminary research results and ongoing work, as well as presentations of research work to a focussed audience.
Therefore, authors will be able to choose, after paper acceptance, if:
* (a) they intend to publish their paper with the conference/workshop proceedings’ editor 
* (b) they do not intend to take advantage of this option (and perhaps submit it elsewhere at a later point in time). 
 
The author's decision of publication mode is done after notification and hence has no bearing on the decision of whether to accept or reject a submission.
Submission implies that at least one author will register and attend the conference if the paper is accepted.
The registration fees for accepted papers is due regardless of the selected publication model.


## Important dates

 * Paper submission: ~~April 18~~ May 2, 2022
 * Paper notification: ~~May 23 2022~~ May 27, 2022
 * Workshop: June 17 2022

## Program chairs
* [Valerio Schiavoni]() (University of Neuchatel)
* [Miguel Matos]() (INESC-ID & U. Lisboa)

## Program committee
 * Hans P. Reiser (Reykjavik University, Island)
 * Francisco Maia (INESC TEC, Portugal)
 * Pierre-Louis Aublin (IIJ Innovation Institute, Japan)
 * Pierre Sutra (Télécom SudParis, France)
 * Heverson Ribeiro (unaffiliated)
 * Nuno Santos (INESC-ID / Instituto Superior Tecnico, Portugal)
 * Marcus	Brandenburger (	IBM Research - Zurich, Switzerland)
 * Marcelo Pasin (University of Neuchatel, Switzerland)
 * Leander	Jehl (TU Braunschweig, Germany)

# Keynote Speakers
 * Pierre Sutra (Télécom SudParis, France)

**Abstract:**
Recent advances in state-machine replication (SMR) protocols focus on leaderless approaches. In these protocols, each replica is on par with its peers and can be used to coordinate the execution of a state-machine command. This removes the bottleneck of leader-based techniques, improves fairness wrt. remote clients as well as availability. To date, few works exist that address arbitrary (byzantine) failures in leaderless SMR. In this talk, we try to bridge this gap. We propose the first general framework to construct correct-by-design byzantine leaderless protocols. Our framework is composed of well-identified services, such as byzantine quorums, best-effort broadcast and consensus. For a given service, many implementations exist. Some may focus on scalability, while others improve latency or security using trusted execution environments (TEE). Two use cases are given to illustrate the framework: a byzantine fault-tolerant variations of Egalitarian Paxos, and a highly scalable byzantine leaderless protocol called Wintermute. We also discuss the interest of byzantine leaderless SMR in the context of permissioned blockchains.

**Bio:**
Pierre Sutra is Associate Professor at Télécom SudParis and a committer of the Apache Software Foundation. His work investigates the theory and practice of distributed systems, with applications to big data stores, transactional systems and storage systems. Pierre has co-authored more than 40 research publications. Over the past two years, he has published at the following top journals and conferences: ACM TOSEM, Information Processing Letters, SOSP, EuroSys, DISC and Middleware.


 * Emanuel Onica (Alexandru Ioan Cuza University, Romania)

**Abstract:** 
Ethereum currently backs the largest amount of existing decentralized applications (DApps) built on public blockchain platforms. Interaction with Ethereum DApps implies transactions that charge a fee. These fees complicate onboarding new users who lack the necessary cryptocurrency. Meta-transaction patterns emerged for decoupling users from paying the transaction fees. In essence, the existing meta-transaction services include a relayer mechanism forwarding the transactions and paying for these on behalf of the users. While solving the user onboarding problem, introducing an extra party in the transaction path generates multiple security issues. In this talk we examine these issues and discuss the first steps taken toward a new meta-transaction architecture that uses Intel Software Guard Extensions (SGX). We argue that integrating a trusted execution environment such as SGX at the relayer site provides the necessary security guarantees in a meta-transaction setting.

**Bio:** 
Emanuel Onica is an Associate Professor at the Faculty of Computer Science, Alexandru Ioan Cuza University of Iaşi, Romania. He received his PhD from University of Neuchâtel, Switzerland, where he worked as a scientific collaborator between 2010 and 2014. He was involved in several European projects, notably coordinating the H2020 EBSIS project between 2016 and 2018. His research interests lie in the area of parallel and distributed systems, where he is the recipient of four awards in international conferences, among which winning the DEBS Grand Challenge in 2017 and 2018. A consistent part of his work in this field has a focus on privacy and security.



# Program
### Program

| When | What | Title and Speaker |
| :---: | :---: | :---: |
| *09.00 - 09.10* | *welcome* | *welcome* |
| **09.15 - 10.00** | Keynote   |  Byzantine Leaderless State-Machine Replication, Pierre Sutra  |
| *10.00 - 10.30* | Invited paper  |  [SplitBFT: Improving Byzantine Fault Tolerance Safety Using Trusted Compartments](https://arxiv.org/abs/2205.08938), TBA |
| *10.30 - 11.00* | Regular paper  |  ContractBox: Using TEEs and WebAssembly for Small Scale Blockchains on the Edge, TBA |
| *11.00 - 11.30* | *coffee break*  |  *coffee break* |
| **11.30 - 12.15** | Keynote   |   Using SGX to Tackle Security Issues in Ethereum Meta-Transactions, Emanuel Onica |
| *12.15 - 12.45* | Regular paper   |   Securing Cross-Chain Asset Transfers on Permissioned Blockchains, TBA |
| *12.45 - 13.00* | *closing*   |  *closing*   |
| *13.00 - 14.30* | *lunch break* | *lunch break*|
