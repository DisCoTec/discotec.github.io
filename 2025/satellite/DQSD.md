# The ∆QSD Paradigm: Designing Systems with Predictable Performance at High Load

## Tutorial Description

The ∆Q Systems Development paradigm (∆QSD) is a novel industrially-derived systems development methodology for developing complex real-world distributed systems, that directly embeds statistically-based performance metrics from the outset of the system design process and throughout the entire software production life cycle. It uses a stochastic approach to specify system behaviour, using cumulative distribution functions to model both delay and failure. Experience shows that this is a ‘sweet spot’ that gives good results with respect to the amount of computation needed. Predictions are accurate when the system model correctly models both independent and dependent parts. This paradigm has been developed by the company PNSol over a period of 20+ years, in collaboration with IOG (formerly IOHK), BT, Vodafone, Boeing Space and Defence, and other major companies who focus on the development of reliable high-quality, high integrity, distributed software systems, with strong real-time requirements.

In this tutorial we will discuss
- how improper random variables can capture the key attribute of ‘quality attenuation’ – a single measure of timeliness and probability of success.
- how convolution, probabilistic choice combined with any- and all-to-finish appears sufficiently rich to capture real world systems.
- many examples and real-world case studies.
- how we are embedding tool support into online notebooks for rapid assessment of design choices and performance issues.
  
The tutorial will be given as a sequence of lectures followed by practice sessions (using our interactive Jupyter notebook). We will give a series of exercises of increasing complexity that showcase bottom-up and top-down design approaches, computation of performance and
feasibility, and exploration of system design trade-offs (such as time-out versus retry for remote operations). We will also do a small number of paper-and-pencil exercises to show how ∆QSD can be used for back-of-the-envelope computations.


## Organization

[Seyed Hossein Haeri]() 

Founder of PLWorkz R&D, former associate professor at the BLDL Institute at the University of Bergen, Norway
