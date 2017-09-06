--- 
layout:  post 
title:   "Type-safe Modular Parsing"
authors: "Li Huang"
date:    2017-03-01 10:00:00 +0800
venue:   "CB 313"
categories: LiHuang Seminar 2017
--- 
## Abstract

Techniques for extending data structures and operations that consume them
have
been extensively studied in a semantic modular way. However, existing works
for
modular parsing only stay in syntactic modularity. The research gap
motivates us
to build modular parsers with static type-safety and separate compilation.
We
show that traditional OO techniques including inheritance and method
overriding
are enough to support modular parsing for OO ASTs. Full extensibility of
ASTs is
achieved by integrating Object Algebras with parsers. More features such as
parsing multi-sorted syntax and modifying existing rules are easily
supported.
Furthermore, the modular parser enables abstracting language features as
components. We conduct a case study of parsers for 18 calculi from book
“Types
and Programming Languages”. The results show the eﬀectiveness at code reuse,
that the total parsing code is 69% shorter than a non-modular
implementation.


