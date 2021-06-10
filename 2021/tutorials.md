[![](https://www.discotec.org/2021/discotec2021-banner.jpeg)](https://www.discotec.org/2021/)

# Tutorials

## Scope

The DisCoTec Tutorial Day allows researchers to promote a *mature* tool that has been under development over the last few years. 
Tutorial session are typically *hands-on*, providing the audience with the unique opportunity to try out the tool under the supervision of those who developed it. This rewards the tool developers for the effort invested in making their tool accessible to the community, fosters cross-fertilisation across the three DisCoTec conferences, and ultimately results in a higher adoption of the presented tools.


## Titles

### ABS: Modeling and analysis with resource-sensitive actors

[Instructions to download and install the tool](https://abs-models.org/getting_started/
)
<br/><br/>
<!-- Tutorial slides [(all)]() and video presentations [(part xxx)]() -->
<!-- <br/><br/> -->
<!-- [Companion tutorial paper]() and [Promo](https://www.youtube.com/watch?v=SC22behYJN0&list=PLG8JZxiRlWS6Wnkkt-ZXXs7yNBtSsUsgP&index=1) -->
<!-- <br/><br/> -->

Actor languages decouple communication from synchronisation, which makes them suitable for distributed and scalable applications with flexible synchronisation patterns, but also facilitates analysis.  
ABS is a timed actor-based modeling language which supports cooperative scheduling and the specification of timing- and resource-aware behavior.  
Cooperative scheduling allows a process which is executing in an actor to be suspended while it is waiting for an event to occur, such that another process which is able to make progress can execute. 
Timed semantics allows the specification of the temporal behavior of the modeled system. 
Resource-aware behavior takes a supply and demand perspective of execution, relating cost centers which provision resources to processes which require them. These modelling concepts have been used in ABS to model cloud computing, e.g., data-processing applications running on the Hadoop platform and micro-services running on containers orchestrated by Kubernetes. 
In this tutorial, we present ABS and its execution environment, and discuss the use of cooperative scheduling and resources in modeling cyber-physical systems and applications deployed on virtualised infrastructure.
<br/><br/>
*Biography:* 
[Einar Broch Johnsen](mailto:einarj@ifi.uio.no) is a professor at the Department of Informatics, University of Oslo. Einar's research focusses on programming models, specification and verification, in particular for concurrent and distributed systems. 
Einar was the coordinator of the EU FP7 project Envisage on formal methods for virtualised services.
[Rudolf Schlatte](mailto:rudi@ifi.uio.no) is a researcher at the Department of Informatics, University of Oslo. His research interests include programming language semantics and compiler implementations.  
He is the principal maintainer of the ABS toolchain.
The ABS modeling language has been developed in collaboration between the University of Oslo, the Technical University of Darmstadt, CWI Amsterdam with contributions from the University of Bologna, the University of Turin, and the Complutense University of Madrid.
<br/><br/>


### Simulation of large scale computational ecosystems with Alchemist: a tutorial

<!-- <br/><br/> -->
<!-- Tutorial slides [(all)]() and video presentations [(part 1)](https://www.youtube.com/watch?v=zF-LHHQjdOg), [(part 2)](https://www.youtube.com/watch?v=nORRuG3VjYU), [(part 3)](https://www.youtube.com/watch?v=crZM6Idpg74) -->
<!-- <br/><br/> -->
<!-- [Companion tutorial paper](https://link.springer.com/chapter/10.1007/978-3-030-78198-9_10) and [Promo](https://www.youtube.com/watch?v=ZIq11I_vTms&list=PLG8JZxiRlWS6Wnkkt-ZXXs7yNBtSsUsgP&index=3) -->
<!-- <br/><br/> -->

Many interesting systems in several disciplines can be modeled as networks of nodes that can store and exchange data: pervasive systems, edge computing scenarios, and even biological and bio-inspired systems. 
These systems feature inherent complexity, and often simulation is the preferred (and sometimes the only) way of investigating their behaviour; this is true both in the design phase and in the verification and testing phase. 
In this tutorial paper, we provide a guide to the simulation of such systems by leveraging Alchemist, an existing research tool used in several works in the literature. 
We introduce its meta-model and its extensible architecture; we discuss reference examples of increasing complexity; and we finally show how to configure the tool to automatically execute multiple repetitions of simulations with different controlled variables, achieving reliable and reproducible results.
<br/><br/>
*Biography:* 
[Danilo Pianini](mailto:danilo.pianini@unibo.it) is a post-doctoral researcher at DISI, the Department of Computer Science and Engineering of the University of Bologna, in Italy. 
He holds a Ph.D. in Computer Science and Engineering, and his main research interests include simulation, (self-organizing) coordination, aggregate computing, pervasive systems, software engineering, agile techniques, and DevOps. On those subjects, he published over 50 articles in international journals and conferences.
He is the lead designer of dozens of open-source software tools, among which the Alchemist simulation platform and the Protelis aggregate programming language.
<br/><br/>


### Tutorial: Designing Distributed Software in mCRL2

<!-- <br/><br/> -->
<!-- Tutorial slides [(all)]() and video presentations [(part 1)](https://youtu.be/N31C1s_p9WM), [(part 2)](https://youtu.be/1udKfJcMVt0), [(part 3)](https://youtu.be/QLX_Vx-KntA) -->
<!-- <br/><br/> -->
[Companion tutorial paper](https://link.springer.com/chapter/10.1007/978-3-030-78089-0_15)
 <!-- and [Promo](https://www.youtube.com/watch?v=SC22behYJN0&list=PLG8JZxiRlWS6Wnkkt-ZXXs7yNBtSsUsgP&index=1) -->
<br/><br/>

Distributed software is very tricky to implement correctly as there are many hard to foresee possible execution orders. 
Proving correctness of such software is hard and time consuming using, for instance, assertional techniques. 
However, behavioural modelling and model checking come to the rescue, as they have become very expressive over the years and are supplied with more than capable tools that allow proving properties quickly. 
Model checking is generally restricted to finite instances of the models of the software, but in our experience this is not at all a real issue. 
Most correctness problems manifest themselves in these limited instances.
In this tutorial we show how to create behavioural models of distributed software, how to specify requirements using modal formulas, and how to verify these. 
For that we use the [mCRL2](https://www.mcrl2.org/web/user_manual/index.html) language and toolset, which is open access and has no restrictions on its use. 
We discuss the design of a number of distributed systems, and how these designs are shaped by the understanding gained through counterexamples.
<br/><br/>
*Biography:* 
[Jan Friso Groote](mailto:j.f.groote@tue.nl) studied computer science at Twente University. 
He obtained his PhD at the University of Amsterdam on process algebra and operational semantics. 
Since 1998 he has been full professor in formal methods at Eindhoven University of Technology. 
His work focusses on methods to improve the quality of software by making models of distributed systems and analyzing such models by mathematical means. 
For this he mostly uses the mCRL2 toolset which contains very expressive model languages and powerful analysis algorithms.
[Jeroen Keiren](mailto:j.j.a.keiren@tue.nl) studied computer science at Eindhoven University of Technology, where he also obtained his PhD on reduction techniques in model checking. 
He has been assistant professor since 2015, and at Eindhoven University of Technology since 2019. 
His work focuses on the development and application of formal methods for the design of reliable software and hardware. 
A common theme in his research is reducing the structures generated in model checking, e.g. using bisimulation methods.
His specific areas of expertise include (explicit state) model checking and parity games.
<br/><br/>

### Better Late than Never or: Verifying Asynchronous Components at Runtime

<!-- <br/><br/> -->
<!-- Tutorial slides [(all)]() and video presentations [(part xxx)]() -->
<!-- <br/><br/> -->
[Companion tutorial paper](https://link.springer.com/chapter/10.1007/978-3-030-78089-0_14)
 <!-- and [Promo]() -->
<br/><br/>

We introduce DetectEr, a runtime verification tool developed over the last 5 years with the aim of monitoring concurrent systems written for the Erlang ecosystem.
DetectEr supports three types of monitoring methods: inline, outline, and offline monitoring.
In *inline monitoring*, the tool statically instruments the system under scrutiny by weaving the monitoring instructions via code injection. 
The ensuing runtime analysis is performed as the weaved system components execute.
*Outline monitoring* allows DetectEr to take a dynamic approach that treats the system as a black box. 
It leverages the tracing infrastructure provided by the Erlang Virtual Machine to gather trace events that are analysed by independent component monitors.
DetectEr also extends outline monitoring to the *offline* case, where events read from a trace dump are replayed to emulate the interaction between concurrent system components.
In this tutorial, we discuss the inline, outline, and offline monitoring functionality of the tool, demonstrating how each can be employed to monitor systems that are subject to specific deployment and runtime constraints.
<br/><br/>
*Biography:* 
[Duncan Paul Attard](https://duncanatt.github.io), #&#8203;breakthrough, is a researcher with the ICE-TCS research group at Reykjavík University. 
He is the principal developer of DetectEr, a runtime verification tool developed as part of the [TheoFoMon](http://icetcs.ru.is/theofomon/)---and more recently---the [MoVeMnt](https://sites.google.com/view/antonisachilleos/movemnt) projects.
Prior to rejoining academia, Duncan worked as a software developer in Telecoms and Online payment industry for seven years.
<br/><br/>
