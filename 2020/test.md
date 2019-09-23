# COORDINATION 2019 - 21st International Conference on Coordination Models and Languages

Coordination 2019 is one of the three conferences of [DisCoTec 2019](https://www.discotec.org/2019/).

<ul class="nav nav-tabs" id="myTab" role="tablist">
  <li class="nav-item">
    <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="true">Call for Papers</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile" aria-selected="false">Accepted Papers</a>
  </li>
</ul>

<!-- START TAB CONTENT -->
<div class="tab-content" id="myTabContent">

  <!-- START CALL FOR PAPERS TAB -->
  <div class="tab-pane fade show active" id="home" role="tabpanel" aria-labelledby="home-tab">

  <!-- HIGHLIGHTS -->
  <h2 id="highlights">Highlights<a class="anchorjs-link " href="#highlights" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em/1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
  <p>Two new categories of submissions added!</p>
  <ul>
    <li><strong><a href="#special-topics">special topics</a></strong>: we seek for contributions that enable the cross-fertilisation with other research communities in computer science or in other engineering or scientific disciplines.</li>
    <li><strong><a href="#tool-papers">tool papers</a></strong>: we seek for video+paper submissions on tools related to coordination</li>
  </ul>
  <p>See the <a href="#submissions">submission section</a> below for details.</p>
  <!-- END HIGHLIGHTS -->

  <!-- KEYNOTE SPEAKERS -->
  <h2 id="keynote-speakers">Keynote Speakers<a class="anchorjs-link " href="#keynote-speakers" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em/1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
  <ul>
  <li><a href="https://www.inf.ethz.ch/personal/basin/">David Basin</a> (ETH Zürich, Switzerland)</li>
  <li><a href="https://www.irisa.fr/asap/?page_id=179">Anne-Marie Kermarrec</a> (INRIA Rennes, France)</li>
  <li><a href="http://www.cs.ox.ac.uk/marta.kwiatkowska/">Marta Kwiatkowska</a> (University of Oxford, UK)</li>
  <li><a href="https://people.csail.mit.edu/silvio/">Silvio Micali</a> (MIT, USA)</li>
  <li><a href="https://www.sosy-lab.org/people/wirsing/">Martin Wirsing</a> (LMU, Germany)</li>
  </ul>
  <!-- END KEYNOTE -->

  <!-- SCOPE -->
  <h2 id="scope">Scope<a class="anchorjs-link " href="#scope" aria-label="Anchor" data-anchorjs-icon="" style="font: 1em/1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
  <p>Modern information systems rely increasingly on combining concurrent, distributed, mobile, adaptive, reconfigurable and heterogeneous components. New models, architectures, languages and verification techniques are necessary to cope with the complexity induced by the demands of today’s software development. Coordination languages have emerged as a successful approach, in that they provide abstractions that cleanly separate behaviour from communication, therefore increasing modularity, simplifying reasoning, and ultimately enhancing software development. Building on the success of the previous editions, this conference provides a well-established forum for the growing community of researchers interested in models, languages, architectures, and implementation techniques for coordination.</p>
  <!-- END SCOPE -->

  </div>
  <!-- END CALL FOR PAPERS TAB -->


  <!-- START ACCEPTED PAPERS -->
  <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">

   <button type="button" class="btn btn-light" data-toggle="modal" data-target="#paper1">
     Forward to a Promising Future. Kiko Fernandez-Reyes, Dave Clarke, Elias Castegren and Huu-Phuc Vo.
   </button>
   <!-- Modal -->
   <div class="modal fade" id="paper1" tabindex="-1" role="dialog" aria-labelledby="Forward-to-a-Promising-Future" aria-hidden="true">
     <div class="modal-dialog modal-dialog-scrollable" role="document">
       <div class="modal-content">
         <div class="modal-header d-block">
         <div class="d-flex">
             <h3 class="modal-title" id="Forward-to-a-Promising-Future">Forward to a Promising Future</h3>
             <button type="button" class="close" data-dismiss="modal" aria-label="Close">
               <span aria-hidden="true">&times;</span>
             </button>
         </div>
         Kiko Fernandez-Reyes, Dave Clarke, Elias Castegren and Huu-Phuc Vo
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
     Aggregation policies for tuple spaces. Linas Kaminskas and Alberto Lluch Lafuente.
   </button>
   <!-- Modal -->
   <div class="modal fade" id="paper2" tabindex="-1" role="dialog" aria-labelledby="Aggregation-policies-for-tuple-spaces" aria-hidden="true">
     <div class="modal-dialog modal-dialog-scrollable" role="document">
       <div class="modal-content">
         <div class="modal-header d-block">
         <div class="d-flex">
           <h3 class="modal-title" id="Aggregation-policies-for-tuple-spaces">Aggregation policies for tuple spaces</h3>
           <button type="button" class="close" data-dismiss="modal" aria-label="Close">
             <span aria-hidden="true">&times;</span>
           </button>
         </div>
         Linas Kaminskas and Alberto Lluch Lafuente
         </div>
         <div class="modal-body">
         Security policies are important for protecting digitalized information, control resource access and maintain secure data storage. This work presents the development of a policy language to transparently incorporate aggregate programming and privacy models for distributed data. We use tuple spaces as a convenient abstraction for storage and coordination. The language has been designed to accommodate well-known models such as k-anonymity
         and (𝜀,𝛿)-differential privacy, as well as to provide generic user-defined policies. The formal semantics of the policy language and its enforcement mechanism is presented in a manner that abstracts away from a specific tuple space coordination language. To showcase our approach, an open-source software library has been developed in the Go programming language and applied to a typical coordination pattern used in aggregate programming applications.
         </div>
         <div class="modal-footer">
           <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
         </div>
       </div>
     </div>
   </div>
  </div>
  <!-- END ACCEPTED PAPERS -->

</div>
<!-- END TAB CONTENT -->

## Program committee chairs
* Emilio Tuosto (University of Leicester, UK - <emilio@le.ac.uk>)
* Hanne Riis Nielson (DTU, Denmark - <hrni@dtu.dk>)

## Program committee
* Stephanie Balzer (CMU, USA)
* Simon Bliudze (INRIA, France)
* Laura Bocchi (University of Kent, UK)
* Chiara Bodei (Università di Pisa, Italy)
* Roberto Bruni (Università di Pisa, Italy)
* Javier Camara (CMU, USA)
* Giovanna Di Marzo Serugendo (University of Geneva, Switzerland)
* Fatemeh Ghassemi (University of Tehran, Iran)
* Elisa Gonzalez Boix (VUB, Belgium)
* Roberto Guanciale (KTH, Sweden)
* Ludovic Henrio (CNRS, France)
* Thomas  Hildebrandt (University of Copenhagen, Denmark)
* Omar Inverso (Gran Sasso Science Institute, Italy)
* Jean-Marie Jacquet (University of Namur, Belgium)
* Eva Kühn (Vienna University of Technology, Austria)
* Michele Loreti (University of Camerino, Italy)
* Mieke Massink (CNR-ISTI, Italy)
* Hernan Melgratti (Universidad de Buenos Aires, Argentina)
* Claudio Antares Mezzina (University of Leicester, UK)
* Rumyana Neykova (Brunel University London, UK)
* Luca Padovani (Università di Torino, Italy)
* Danilo Pianini (University of Bologna, Italy)
* Christian W. Probst (Unitec Institute of Technology, New Zealand)
* Rene Rydhof Hansen (Aalborg University, Denmark)
* Gwen Salaün (University of Grenoble Alpes, France)
* Meng Sun (Peking University, China)
* Carolyn Talcott (SRI International, USA)
* Hugo Torres Vieira (IMT School for Advanced Studies Lucca, Italy)
* Takuo Watanabe (Tokyo Institute of Technology, Japan)


## Steering committee
* Gul Agha, University of Illinois at Urbana Champaign, USA
* Farhad Arbab, CWI and Leiden University, The Netherlands
* Rocco De Nicola, IMT - School for Advanced Studies, Italy
* Giovanna di Marzo Serugendo, Université de Genève, Switzerland
* Tom Holvoet, KU Leuven, Belgium
* Jean-Marie Jacquet, University of Namur, Belgium
* Christine Julien, The University of Texas at Austin, USA
* Eva Kühn, Vienna University of Technology, Austria
* Alberto Lluch Lafuente, Technical University of Denmark, Denmark
* Michele Loreti, University of Camerino, Italy
* Mieke Massink, ISTI CNR, Italy
* Wolfgang De Meuter, Vrije Universiteit Brussels, Belgium
* Jose Proença, University of Minho, Portugal
* Rosario Pugliese, Università di Firenze, Italy
* Marjan Sirjani, Reykjavik University, Iceland
* Carolyn Talcott, SRI International, California, USA
* Vasco T. Vasconcelos, University of Lisbon, Portugal
* Gianluigi Zavattaro, University of Bologna, Italy (Chair)
* Mirko Viroli, University of Bologna, Italy
