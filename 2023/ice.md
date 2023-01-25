[![](discotec2023-banner.v3.png)](https://www.discotec.org/2023/)

# ICE 2023 - 16th Interaction and Concurrency Experience

Interaction and Concurrency Experiences (ICE) is a series of international scientific meetings oriented to theoretical computer science researchers with special interest in models, verification, tools, and programming primitives for concurrent systems and complex interactions. ICE 2023 is a satellite workshop of [DisCoTec 2023](https://www.discotec.org/2023/), held on Monday 19th June 2023 at the [NOVA University](https://www.unl.pt/en) in Lisbon, Portugal.

<!--
**COVID-19:** ICE 2023 will be a physical, in-person event, with some support for remote presence, both for speakers and for other participants who are unable or unwilling to come.

**ICE 2023 Dinner**: 17 June, **21:30 at [Mara Meo](https://g.page/Mara-Meo-SanFrancesco)** - Piazza San Francesco, Lucca.
_(If you wish to join but have not filled the attendance sheet, please contact `ice2023 (at) framalistes.org`)_

See the [**ICE 2023 programme and pre-proceedings**](#programme), and [proceedings](http://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2022).
-->

## Highlights

- Distinctive selection procedure
- ICE welcomes full papers to be included in the proceedings
- ICE also welcomes oral communications of already published or preliminary work
- Invited speakers: To be announced.
- Publication in [EPTCS](https://eptcs.org/).
- Special issue in the [Journal of Logical and Algebraic Methods in Programming](https://www.journals.elsevier.com/journal-of-logical-and-algebraic-methods-in-programming) (Elsevier) _(to be confirmed)_
- Contact: `ice2023 (at) framalistes.org`

## Scope

The general scope of the venue includes theoretical and applied aspects of interactions and the synchronization mechanisms used among components of concurrent/distributed systems, related to several areas of computer science in the broad spectrum ranging from formal specification and analysis to studies inspired by emerging computational models.

We solicit contributions relevant to Interaction and Concurrency, including but not limited to:

- Formal semantics
- Process algebras and calculi
- Models and languages
- Protocols
- Logics and types
- Expressiveness
- Model transformations
- Tools, implementations, and experiments
- Specification and verification
- Coinductive techniques
- Tools and techniques for automation
- Synthesis techniques


<!--
## Programme and Pre-proceedings {#programme}

You can download the [**ICE 2023 pre-proceedings**](ice22-preproceedings.pdf).
The proceedings are also [available as EPTCS 365](http://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2022).

The talks will take place at **Cappella Guinigi**.

*All times are listed for* [**CEST** *(Central European Summer Time)*](https://time.is/CEST)


| Time CEST   | Session | Talk |
| ------------| ------- | ---- |
| 9:00-9:10   | Opening | _Welcome to ICE 2023_ |
| **9:10-10:10**  | **Invited talk** | [**Matthew Parkinson (Microsoft Research UK)**: _Project Verona's Concurrency Model_](#matthew-parkinson)
| 10:10-10:40 | Verification | Eduard Kamburjan, Nathan Wasser: _The Right Kind of Non-Determinism: Using Concurrency to Verify C Programs with Underspecified Semantics_ |
| 10:40-11:00 |              | Muhammad Usama Sardar, Christof Fetzer: _Demystifying Attestation in Intel Trust Domain Extensions (TDX) via Formal Verification_ (oral communication)
| **11:00-11:30** | **Coffee break** | |
| 11:30-12:00 | Communication models | Gerard Tabone, Adrian Francalanza: _Session Fidelity for ElixirST: A Session-Based Type System for Elixir Modules_ |
| 12:00-12:30 |                      | Luc Edixhoven, Guillermina Cledou, José Proença, Sung-Shik Jongmans: _Branching pomsets for choreographies_ |
| 12:30-13:00 |                      | Franco Barbanera, Ivan Lanese, Emilio Tuosto: _On Composing Communicating Systems_ |
| **13:00-14:30** | **Lunch break** | |
| **14:30-15:30** | **Invited talk** | [**Ilaria Castellani (INRIA)**: _Global types and event structure semantics for asynchronous multiparty sessions_](#ilaria-castellani)
| 15:30-16:00 | Monitoring | Matteo Cimini: _Lang-n-Send Extended: Sending Regular Expressions to Monitors_ |
| **16:00-16:30** | **Coffee break** | |
| 16:30-16:50 | Oral communications | Marco Bernardo, Claudio Antares Mezzina: _The NiRvAna project: Noninterference and Reversibility Analysis in Private Blockchains_ |
| 16:50-17:10 |                     | Michele Loreti, Michela Quadrini: _A Framework for Modeling Behaviour of Aggregated Agents_ |
| 17:10-17:40 | Discussion | _The ICE Workshop: Past, Present, and Future_ |
| 17:40-17:50 | Conclusion | |


## Invited Speakers 

### Matthew Parkinson

#### Talk: Project Verona's Concurrency Model

> Project Verona is a research programming language exploring various interactions between ownership, memory management and concurrency.  In this talk, I will present its concurrency model, which enables asynchronously creating atomic and ordered units of work with exclusive access to a collection of independent resources. I will demonstrate the approach through a series of pedagogical examples, and briefly discuss both the implementation and the performance of the paradigm.

#### Biography

[Matthew Parkinson](https://www.microsoft.com/en-us/research/people/mattpark/) is a Principal Researcher at Microsoft Research. Prior to joining Microsoft in 2010, he spent four years as a RAEng/EPSRC research fellowship at the University of Cambridge, where he also did his Ph.D..

His research focusses on Concurrency and Ownership, with a particular focus on memory safety. His recent research focusses on [Project Verona](https://github.com/microsoft/verona) and its allocator [snmalloc](https://github.com/microsoft/snmalloc).  Project Verona is a new language to explore research about efficient and safe ways to manage memory.

### Ilaria Castellani

#### Talk: Global types and event structure semantics for asynchronous multiparty sessions

> In this talk, I will address the connection between multiparty session types (MPSTs) and event structures (ESs), focussing on a core asynchronous session calculus and on two simple classes of ESs, Prime ESs and Flow ESs. I will first introduce a new notion of global type for asynchronous multiparty sessions, which splits the standard communication construct of MPSTs in two constructs (one for output and one for input), and show that this new typing ensures the expected properties for asynchronous sessions, including progress.
>
> I will then present an interpretation of asynchronous multiparty sessions as Flow ESs and an interpretation of our new global types as Prime ESs. I will conclude with our main result, stating that the ES interpretation of a session is equivalent, when the session is typable, to the ES interpretation of its type, namely, that the two interpretations yield isomorphic domains of configurations.
>
> Based on joint work with Mariangiola Dezani-Ciancaglini and Paola Giannini.

#### Biography

[Ilaria Castellani](https://www-sop.inria.fr/members/Ilaria.Castellani/) is a senior researcher at INRIA Sophia Antipolis, France. Her main research interests are in non-interleaving semantics for process calculi, language-based security for concurrent programs and processes, and multiparty session types. She was the chair of the IFIP TC1 Working Group 1.8 on Concurrency Theory from 2014 to 2020. 

-->

## Important Dates

The following dates are in the [Anywhere on Earth time zone](https://time.is/Anywhere_on_Earth).

- 27 March 2023: abstract submission
- 3 April 2023: paper submission
- 8 May 2023: notification
- June 19 or 23: ICE workshop
- 20 July 2023: camera-ready for EPTCS post-proceedings


## The ICE Selection Procedure

Since [its first edition in 2008](#previous-editions), the distinguishing feature of ICE has been an innovative paper selection mechanism based on an interactive, friendly, and constructive discussion amongst authors and PC members in an online forum.

During the review phase, each submission is published in a dedicated discussion forum. The discussion forum can be accessed by the authors of the submission and by all PC members not in conflict with the submission (the forum preserves anonymity). The forum is used by reviewers to ask questions, clarifications, and modifications from the authors, allowing them better to explain and to improve all aspects of their submission. The evaluation of the submission will take into account not only the reviews, but also the outcome of the discussion.

As witnessed by the past editions of ICE, this procedure considerably improves the accuracy of the reviews, the fairness of the selection, the quality of camera-ready papers, and the discussion during the workshop.

ICE adopts a light double-blind reviewing process, [detailed below](#submission-guidelines).


## Submission Guidelines

Submissions must be made electronically in PDF format via [OpenReview](https://openreview.net/group?id=DisCoTec.org/2023/Workshop/ICE).

We invite two types of submissions:

* **Research papers**, original contributions that will be published in the workshop post-proceedings. Research papers must not be simultaneously submitted to other conferences/workshops with refereed proceedings. Research papers should be 3-16 pages plus at most 2 pages of references. Short research papers are welcome; for example a 5 page short paper fits this category perfectly. The submitted PDF can use any LaTeX style (but the post-proceedings will use the [EPTCS style](http://style.eptcs.org/)).

* **Oral communications** will be presented at the workshop, but will not appear in the post-proceedings. This type of contribution includes e.g.,  previously published contributions, preliminary work, and position papers. There is no strict page limit for this kind of submission but papers of 1-5 pages would be appreciated. For example, a one page summary of previously published work is welcome in this category.

Authors of research papers must omit their names and institutions from the title page, they should refer to their other work in the third person and omit acknowledgements that could reveal their identity or affiliation. The purpose is to avoid any bias based on authors' identity characteristics, such as gender, seniority, or nationality, in the review process. Our goal is to facilitate an unbiased approach to reviewing by supporting reviewers' access to works that do not carry obvious references to the authors' identities. As mentioned above, this is a lightweight double-blind process. Anonymization should not be a heavy burden for authors, and should not make papers weaker or more difficult to review. Advertising the paper on alternate forums (e.g., on a personal web-page, pre-print archive, email, talks, discussions with colleagues) is permitted, and authors will not be penalized by for such advertisement.

Papers in the "Oral communications" category need not be anonymized. For any questions concerning the double blind process, feel free to consult the ICEcreamers.

We are keen to enhance the balanced, inclusive and diverse nature of the ICE community, and would particularly encourage female colleagues and members of other underrepresented groups to submit their work.


## Publications

Accepted research papers and communications must be presented at the workshop by one of the authors.

Accepted research papers will be published after the workshop in [Electronic Proceedings in Theoretical Computer Science](http://about.eptcs.org/).

We plan to invite authors of selected papers and brief announcements to submit their work in a special issue in the [Journal of Logical and Algebraic Methods in Programming](https://www.journals.elsevier.com/journal-of-logical-and-algebraic-methods-in-programming) (Elsevier) _(to be confirmed)_. Such contributions will be regularly peer-reviewed according to the standard journal policy, but they will be handled in a shorter time than regular submissions. A list of published and in preparation special issues of previous ICE editions is reported below.


## ICEcreamers

- [Clément Aubert](https://spots.augusta.edu/caubert/)  (Augusta University, USA) - `aubert (at) math.cnrs.fr`
- [Cinzia Di Giusto](https://www.i3s.unice.fr/digiusto/node/1) (Université Côte d'Azur, CNRS, I3SSophia Antipolis, FR) - `cinzia.di-giusto (at) unice.fr`
- [Simon Fowler](http://www.simonjf.com/) (University of Glasgow School of Computing Science, GB-SCT) - `simon.fowler (at) glasgow.ac.uk`
- [Larisa Safina](https://lsafina.github.io/) (Inria, FR) - `larisa.safina (at) inria.fr`

Use `ice2023 (at) framalistes.org` to reach all the ICEcreamers at once.

## Programme Committee {#programme-committee}


- [Duncan Paul Attard](https://duncanatt.github.io/) (Reykjavík University, IS) 
- [Massimo Bartoletti](https://tcs.unica.it/members/bart) (Università di Cagliari, IT) 
- [Davide Basile](https://davidebasile.github.io/) (ISTI CNR, IT) 
- [Hélène Coullon](https://helene-coullon.fr/) (IMT Atlantique, FR) 
- [Jovana Dedeić](http://imft.ftn.uns.ac.rs/math/People/JovanaRadenovi%C4%87) (Faculty of Technical Sciences, University of Novi Sad, RS) 
- [Luc Edixhoven](https://www.cwi.nl/people/luc-edixhoven) (Centrum Wiskunde & Informatica, NL) 
- [Saverio Giallorenzo](https://www.saveriogiallorenzo.com/) (University of Bologna, IT) 
- [Keigo Imai](https://keigoimai.info/) (Gifu University, JP) 
- [Sung-Shik Jongmans](http://sungshik.github.io/) (Open University of the Netherlands, NL) 
- [Eduard Kamburjan](https://www.mn.uio.no/ifi/english/people/aca/eduard/) (University of Oslo, NO) 
- [Sergueï Lenglet](https://members.loria.fr/SLenglet/)  (Université de Lorraine, FR) 
- [Diego Marmsoler](https://www.marmsoler.com/) (University of Exeter, GB) 
- [Anastasia Mavridou](http://amavridou.com/) (NASA Ames, USA) 
- [Doriana Medić](https://alpha.di.unito.it/doriana-medic/) (University of Turin, IT) 
- [Ivan Prokić](http://imft.ftn.uns.ac.rs/~iprokic/Main) (Faculty of Technical Sciences, University of Novi Sad, RS) 
- [Matteo Sammartino](https://matteosammartino.com/)  (Royal Holloway, University of London, GB) 
- [Amrita Suresh](https://amritasuresh.github.io/) (ENS Paris Saclay, FR) 
- [Gerard Tabone](https://gerardtabone.com/) (University of Malta, MT) 
- [Fangyi Zhou](http://www.doc.ic.ac.uk/~fz315/) (Imperial College London, GB) 


<!--
★

★ **The _ICE 2023 Outstanding PC Member Award_ was awarded to <FILL>!**
-->

## Steering Committee

# Steering Committee

- [Massimo Bartoletti](https://tcs.unica.it/members/bart) (University of Cagliari, IT)
- [Ludovic Henrio](https://lhenrio.github.io/) (ENS Lyon, FR)
- [Sophia Knight](https://www.lix.polytechnique.fr/~sophia/) (University of Minnesota Duluth, USA)
- [Ivan Lanese](https://www.cs.unibo.it/~lanese/) (University of Bologna, IT)
- [Alceste Scalas](https://www.imm.dtu.dk/~alcsc/) (Technical University of Denmark, DK)
- [Hugo Torres Vieira](https://scholar.google.com/citations?user=Y5yb7XEAAAAJ&hl=en) (Evidence Srl, IT)


## Previous Editions

The previous editions of ICE have been held on:

- [ICE'22](https://www.discotec.org/2022/ice), June 17, 2022 in Lucca, Italy, co-located with [DisCoTec'22](https://www.discotec.org/2022/). The post-proceedings were published in [EPTCS (vol. 365)](http://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2022) and selected papers are currently being reviewed to appear in a special issue of [JLAMP](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming/).
- [ICE'21](http://www.discotec.org/2021/ice), June 18, 2020, online event co-located with [DisCoTec'21](https://www.discotec.org/2021/). The post-proceedings were published in [EPTCS (vol. 347)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2021) and selected papers appeared in a special issue of [JLAMP](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming/special-issue/106L7VVC5FC).
- [ICE'20](http://www.discotec.org/2020/ice), June 19, 2020, online event co-located with [DisCoTec'20](https://www.discotec.org/2020/). The post-proceedings were published in [EPTCS (vol. 324)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2020) and two papers appeared in JLAMP ([10.1016/j.jlamp.2021.100712](https://doi.org/10.1016/j.jlamp.2021.100712) and [10.1016/j.jlamp.2022.100776](https://doi.org/10.1016/j.jlamp.2022.100776)).
- [ICE'19](http://www.discotec.org/2019/ice), June 20-21, 2019 in Lyngby, Denmark, co-located with [DisCoTec'19](https://www.discotec.org/2019/). The post-proceedings were published in [EPTCS (vol. 304)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2019) and selected papers appeared in a special issue of [JLAMP](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming/special-issue/101ZSK6ZFQ4).
- [ICE'18](http://2018.discotec.org/cfp_w_ice.html), June 20-21, 2018 in Madrid, Spain, co-located with DisCoTec'18. The post-proceedings were published in [EPTCS (vol. 279)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2018) and selected papers appeared in a special issue of [JLAMP](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming/special-issue/10XN45J051V).
- [ICE'17](http://2017.discotec.org/workshops/ice-2017.html), June 21-22 2017 in Neuchâtel, Switzerland, co-located with DisCoTec'17. The post-proceedings were published in [EPTCS (vol. 261)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2017) and a special issue of [JLAMP (Vol. 109)](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming/vol/109).
- [ICE'16](http://2016.discotec.org/index713e.html), June 21-22, 2016 in Heraklion, Greece, co-located with DisCoTec'16. The post-proceedings were published in [EPTCS (vol. 223)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2016) and a special issue of [JLAMP (Vol. 92)](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming/vol/92).
- [ICE'15](http://discotec2015.inria.fr/workshops/ice-2015/), June 4-5, 2015 in Grenoble, France, co-located with DisCoTec'15. The post-proceedings were published in [EPTCS (vol. 189)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2015) and selected papers appeared in a special issue of [JLAMP (Vol. 86, Number 1)](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming/vol/86).
- [ICE'14](http://www.discotec2014.tu-berlin.de/workshops/ice-2014), June 6, 2014 in Berlin, Germany, co-located with DisCoTec'14. The post-proceedings were published in [EPTCS (vol. 166)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2014) and selected papers appeared in a special issue of [JLAMP (Vol. 85, Number 3)](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming/vol/86/issue/3).
- [ICE'13](http://2013.discotec.org/workshops/ice2013/), June 6, 2013 in Florence, Italy, co-located with DisCoTec'13. The post-proceedings were published in [EPTCS (vol. 131)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2013) and selected papers appeared in a special issue of [SCP (vol. 109)](https://www.sciencedirect.com/journal/science-of-computer-programming/vol/109).
- [ICE'12](http://www.artist-embedded.org/artist/Overview,2429.html), June 16, 2012 in Stockholm, Sweden, co-located with DisCoTec'12. The post-proceedings were published in [EPTCS (vol. 104)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2012) and selected papers appeared in a special issue of [SCP (vol. 100)](https://www.sciencedirect.com/journal/science-of-computer-programming/vol/100).
- [ICE'11](http://www.artist-embedded.org/artist/-ICE-2011-.html), June 9, 2011 in Reykjavik, Iceland, co-located with DisCoTec'11. The post-proceedings were published in [EPTCS (vol. 59)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2011) and selected papers appeared in a special issue of [SACS (Vol. XXII)](https://www.info.uaic.ro/en/sacs_volumes/xxii-1/).
- [ICE'10](http://www.artist-embedded.org/artist/-ICE-10-.html) June 10, 2010 in Amsterdam, The Netherlands, co-located with DisCoTec'10. The post-proceedings were published in [EPTCS (vol. 38)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2011) and selected papers appeared in a joint special issue of [SACS (with CAMPUS'10 and CS2BIO'10, Vol. XXI)](https://www.info.uaic.ro/en/sacs_volumes/xxi-1/).
- [ICE'09](http://ice09.dimi.uniud.it/) August 31, 2009 in Bologna, Italy, co-located with CONCUR'09. The post-proceedings were published in [EPTCS (vol. 12)](https://eptcs.web.cse.unsw.edu.au/content.cgi?ICE2009) and selected papers appeared in a joint special issue of [MSCS (with EXPRESS'09 and SOS'09, Vol. 22, Number 2)](https://www.cambridge.org/core/journals/mathematical-structures-in-computer-science/issue/4A7319C7211730C6521DB797E0B53668).
- [ICE'08](http://ice08.dimi.uniud.it/), July 6, 2008 in Reykjavik, Iceland, co-located with ICALP'08. The post-proceedings were published in [ENTCS (vol. 229-3)](https://dl.acm.org/toc/entcs/2009/229/3).


## More Information

For additional information, please [contact the ICEcreamers](#icecreamers) at `ice2023 (at) framalistes.org`.
