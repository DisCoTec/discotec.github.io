# COORDINATION 2019 - 21st International Conference on Coordination Models and Languages

Coordination 2019 is one of the three conferences of [DisCoTec 2019](https://www.discotec.org/2019/).


## Highlights

Two new categories of submissions added!
* **[special topics](#special-topics)**: we seek for contributions that enable the cross-fertilisation with other research communities in computer science or in other engineering or scientific disciplines.
* **[tool papers](#tool-papers)**: we seek for video+paper submissions on tools related to coordination

See the [submission section](#submissions) below for details.


## Keynote Speakers
* [David Basin](https://www.inf.ethz.ch/personal/basin/) (ETH Zürich, Switzerland)
* [Anne-Marie Kermarrec](https://www.irisa.fr/asap/?page_id=179) (INRIA Rennes, France)
* [Marta Kwiatkowska](http://www.cs.ox.ac.uk/marta.kwiatkowska/) (University of Oxford, UK)
* [Silvio Micali](https://people.csail.mit.edu/silvio/) (MIT, USA)
* [Martin Wirsing](https://www.sosy-lab.org/people/wirsing/) (LMU, Germany)

## Scope
Modern information systems rely increasingly on combining concurrent, distributed, mobile, adaptive, reconfigurable and heterogeneous components. New models, architectures, languages and verification techniques are necessary to cope with the complexity induced by the demands of today's software development. Coordination languages have emerged as a successful approach, in that they provide abstractions that cleanly separate behaviour from communication, therefore increasing modularity, simplifying reasoning, and ultimately enhancing software development. Building on the success of the previous editions, this conference provides a well-established forum for the growing community of researchers interested in models, languages, architectures, and implementation techniques for coordination.

## Accepted Papers 2018

<button type="button" class="btn btn-light" data-toggle="modal" data-target="#paper1">
  Kiko Fernandez-Reyes, Dave Clarke, Elias Castegren and Huu-Phuc Vo. Forward to a Promising Future
</button>

<!-- Modal -->
<div class="modal fade" id="paper1" tabindex="-1" role="dialog" aria-labelledby="Forward-to-a-Promising-Future" aria-hidden="true">
  <div class="modal-dialog modal-dialog-scrollable" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="Forward-to-a-Promising-Future">Forward to a Promising Future</h5>
        <h6 class="pl-2">Kiko Fernandez-Reyes, Dave Clarke, Elias Castegren and Huu-Phuc Vo</h6>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
      In many actor-based programming models, asynchronous method calls communicate their results using futures,
 where the fulfilment occurs under-the-hood. Promises play a similar role to futures, except that they must be explicitly created and explicitly fulfilled;
this makes promises more flexible than futures, though promises lack fulfilment guarantees: they can be fulfilled once, multiple times or not at all. Unfortunately, futures are too rigid to exploit many available concurrent and parallel patterns. For instance, many computations block on a future to get its result only to return that result immediately (to fulfil their own future).
To make futures more flexible, we explore a construct, forward, that delegates the responsibility for fulfilling the current implicit future to another computation. Forward reduces synchronisation and gives futures promise-like capabilities. This paper presents a formalisation of the forward construct, defined in a high-level source language, and a compilation strategy from the high-level language to a low-level, promised-based target language.
The translation is shown to preserve semantics. Based on this foundation, we describe the implementation of forward in the parallel, actor-based language Encore, which compiles to C.
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>


<button type="button" class="btn btn-light" data-toggle="modal" data-target="#paper2">
  Linas Kaminskas and Alberto Lluch Lafuente. Aggregation policies for tuple spaces
</button>

<!-- Modal -->
<div class="modal fade" id="paper2" tabindex="-1" role="dialog" aria-labelledby="Aggregation-policies-for-tuple-spaces" aria-hidden="true">
  <div class="modal-dialog modal-dialog-scrollable" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="Aggregation-policies-for-tuple-spaces">Aggregation policies for tuple spaces</h5>
        <h6 class="pl-2">Linas Kaminskas and Alberto Lluch Lafuente</h6>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
      In many actor-based programming models, asynchronous method calls communicate their results using futures,
 where the fulfilment occurs under-the-hood. Promises play a similar role to futures, except that they must be explicitly created and explicitly fulfilled;
this makes promises more flexible than futures, though promises lack fulfilment guarantees: they can be fulfilled once, multiple times or not at all. Unfortunately, futures are too rigid to exploit many available concurrent and parallel patterns. For instance, many computations block on a future to get its result only to return that result immediately (to fulfil their own future).
To make futures more flexible, we explore a construct, forward, that delegates the responsibility for fulfilling the current implicit future to another computation. Forward reduces synchronisation and gives futures promise-like capabilities. This paper presents a formalisation of the forward construct, defined in a high-level source language, and a compilation strategy from the high-level language to a low-level, promised-based target language.
The translation is shown to preserve semantics. Based on this foundation, we describe the implementation of forward in the parallel, actor-based language Encore, which compiles to C.
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
