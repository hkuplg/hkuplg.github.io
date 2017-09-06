--- 
layout:  post 
title:   "Disjoint Intersection Types"
authors:  "João"
time:     2016-04-01 16:00:00
venue:   "CB 328"
categories: "João" Seminar 2016
--- 
## Abstract

Dunfield showed that a simply typed core calculus with intersection types
and a
merge operator is able to capture various programming language features.
While
his calculus is type-safe, it is not coherent: different derivations for the
same expression can lead to different results. The lack of coherence is an
important disadvantage for adoption of his core calculus in implementations
of
programming languages, as the semantics of the programming language becomes
implementation-dependent.

It will be presented λi: a coherent and type-safe calculus with a form of
intersection types and a merge operator. Coherence is achieved by ensuring
that
intersection types are disjoint and programs are sufficiently annotated to
avoid
type ambiguity. Another two variants of λi will be discussed, which include
a
top type and different definitions of disjointness. For all three
variations of
λi, it will also be shown an algorithmic specification for computing
whether two
types are disjoint or not.


