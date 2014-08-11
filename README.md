Scone is a knowledge representation and reasoning system – a knowledge-base system or KBS – that has been developed by Scott Fahlman’s research group in the Language Technologies Institute of Carnegie Mellon University.  Scone, by itself, is not a complete AI or decision-making system, and does not aspire to be; rather, it is a software component – a sort of smart active memory system – that is designed to be used in a wide range of software applications, both in AI and in other areas.  Scone deals just with symbolic knowledge. Things like visualization, motor memory, and memory for sound sequences are also important for human-like intelligence, but we believe that those will have specialized representations of their own, linked in various ways to the symbolic memory.

Scone occupies a different part of the design space from other knowledge-base systems currently in use – particularly systems such as OWL that are based on First-Order Logic or Description Logic.  Our goal in developing Scone has been to support common-sense reasoning and natural-language understanding, not theorem-proving and logic puzzles.  Therefore, we place primary emphasis on Scone's expressiveness, ease of use, and scalability.

In addition to making Scone available to a larger community, and building up the necessary supporting machinery, our goals include adding more episodic representation and reasoning capabilities to Scone.  By "episodic", we mean the ability to represent and reason about events, actions, sequences, plans, goals, time durations, processes and rates, and so on.  In addition, we are working on knowledge-based natural language understanding based on Scone.

The Scone release indcludes the Scone engine, a large program written in Common Lisp; a set of "core" knowledge base files that are useful in most common-sense applications; and the Scone User's Guide, a programmer-level manual on Scone.  Work on comprehensive tutorial book on Scone (primarily packaged as an electornic book with lots of cross references) is under way, but not yet available.  Scone is under active development, and we anticipate that there will be a lot of changes to the system over the next few months.

The core capabilities of Scone have been running for several years, and have been used in a number of projects at CMU and by a few outside collaborators.  It has always been our intention to release Scone as an open-soure resource for the research community and other potential users.  Our research group is very small at present, and we are all very busy on our ongoing research efforts on Scone and related applications (plus the never-ending quest to keep the project funded).  So we welcome comments, queries, contributions, suggestions, and even requests for new functionality, but we cannot promise anything in the way of timely support for external users and potential contributors.  So for now, Scone is for the adventurous and for those who can answer some of their own questions by looking at our code and assorted documents and papers.

For additional information about Scone, please see our [Scone project home page](http://www.cs.cmu.edu/~sef/scone/).  Additional information on our overall goals and approach, and some assorted other musings about AI, are on Scott Fahlman's [Knowledge Nuggets blog](www.cs.cmu.edu/~nuggets).


