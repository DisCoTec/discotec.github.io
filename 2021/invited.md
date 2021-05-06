[![](https://www.discotec.org/2021/discotec2021-banner.jpeg)](https://www.discotec.org/2021/)

# Invited Speakers

## Alexandra Silva 

[University College London, UK](mailto:alexandra.silva@ucl.ac.uk)  

###  Prognosis: Black-Box Analysis of Network Protocol Implementations

<!-- Presentation 
[slides](./slides/invited/DisCoTec20-NB.pdf) and [video](https://www.youtube.com/watch?v=xIOk6rFQkAc&feature=youtu.be)
--> 

We present Prognosis, a framework offering automated black-box learning and analysis of models of network protocol implementations. 
Prognosis can learn models that vary in abstraction level from simple deterministic automata to models containing data operations, such as register updates, and can be used to unlock a variety of analysis techniques — model checking temporal properties, computing differences between models of two implementations of the same protocol, or improving testing via model-based test generation. 
Prognosis is modular and easily adaptable to different pro- tocols (e.g., TCP and QUIC) and their implementations. 
We use Prognosis to learn models of (parts of) three QUIC implementations—Quiche (Cloudflare), Google QUIC, and Facebook mvfst—and use these models to analyze the differences between the various implementations. 
Our analysis provides insights into different design choices and uncovers potential bugs. 
Concretely, we have found critical bugs in multiple QUIC implementations, which have been acknowledged by the developers.
This is joint work with Tiago Ferreira (UCL), Harrison Brewton and Loris D’Antoni (University of Wisconsin–Madison).

### Biography
Alexandra Silva is a theoretical computer scientist whose main research focuses on semantics of programming languages and modular development of algorithms for computational models. A lot of her work uses the unifying perspective offered by coalgebra, a mathematical framework established in the last decades.  
Alexandra is currently a Professor of Algebra, Semantics, and Computation at University College London and will be joining Cornell University in the fall of 2021. 
Previously, she was an assistant professor in Nijmegen and a postdoc at Cornell University, with Prof. Dexter Kozen, and a PhD student at the Dutch national research center for Mathematics and Computer Science (CWI), under the supervision of Prof. Jan Rutten and Dr. Marcello Bonsangue. 
She was the recipient of an ERC Consolidator Grant in 2020, the Royal Society Wolfson Award 2019, Needham Award 2018, the Presburger Award 2017, the Leverhulme prize 2016, and an ERC starting Grant in 2015.


## Mira Mezini

[Technical University of Darmstadt, DE](mailto:mezini@st.informatik.tu-darmstadt.de)

### Let it Flow:  Reactive Computations for Consistent-by-Design Distributed Applications

<!--Presentation [video](https://youtu.be/v3S6lhKOFPU) -->

Ubiquitous connectivity of millions of powerful (mobile) devices to each other and to web and cloud computing platforms via programmable networks has created globally and massively distributed computing systems---the information power grids of the 21st century---and has fuelled the development of massively distributed applications.  
Today, distributed applications often rely on centralized servers/clouds for consistency management. 
However, centralized consistency management is not a good match for massively distributed computing systems due to problems with offline availability, low latency, or user-control on data privacy, etc. 
Decentralized architectures with decentralized state and local-first computations are a better match for globally distributed computing systems. 
However, when building applications for such architectures, developers are left with the responsibility of handling partial failures at the application layer, thereby trading off between high availability and strong consistency. 

In the talk, I will argue for and discuss language-based solutions automating hybrid consistency decisions. 
With such solutions, it is the responsibility of the language machinery to reason about consistency levels and to make use of hybrid consistency systems as needed by the application semantics. 
As a result, such languages offer developers well-defined and formally-proven guarantees “out-of-the-box”. 
I will specifically focus on how declarative reactive programming abstractions help in automatically handling the challenges of decentralization by providing decentralized concurrency control and fault-tolerance with well-defined consistency guarantees. I will present my thoughts in the context of REScala (rescala-lang.com)---a library-based extension to the programming language Scala---that my team and me have designed and implemented in the recent past. 
In the reactive style of REScala, applications are modelled as compositions of reactive abstractions, which denote time-changing values resulting from computations with reactive application semantics (i.e., computations are automatically executed whenever their inputs change). 
I will elaborate on how this model in synergetic combination with concepts from multi-version consistency control, asynchronous distributed computing, and invariant-based verification enable a language-based management of application consistency in concurrent and distributed settings with well-defined guarantees.    

### Biography

Mira Mezini obtained a doctorate degree from the University of Siegen (Germany) in 1997 and was visiting assistant professor at Northeastern University (USA), before becoming professor of computer science at Technical University of Darmstadt (Germany) in 2000. 
From 2013 to 2016, she additionally held a visiting professorship at Lancaster University (UK). 
Mira leads the chair for software technology at TU Darmstadt. 
Her research focuses in software analysis and programming language design with applications in networked software systems, software security, and AI systems.  
Mira Mezini was selected to the German Academy of Science and Engineering (acatech) in 2016. 
She has received various research awards, including two IBM Innovation Awards, a Google Research Award, and most notably FGan ERC Advanced Grant in 2013, the EU's most highly endowed funding award. 
Has published more than 180 papers, many of which in top venues across the areas of programming languages and software engineering, and serves regularly in program committees and editorial boards of conferences and journals in these areas.




