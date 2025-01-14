--- 
layout:  post 
title:   Two Practice Talks for POPL
authors: Shengyi & Litao
date:    2025-01-15 10:00:00 +0800
venue:   Zoom
--- 

Due to FYP presentations occupying meeting rooms, we will have our practice
talks on Zoom. Please join the meeting with the following link:


Topic: PL Group Seminar
Time: Jan 15, 2025 10:00 AM Hong Kong SAR

Join Zoom Meeting
https://hku.zoom.us/j/94336051031

Meeting ID: 943 3605 1031



### Bidirectional Higher-Rank Polymorphism with Intersection and Union Types

Modern mainstream programming languages, such as TypeScript, Flow, and Scala,
have polymorphic type systems enriched with intersection and union types. These
languages implement variants of *bidirectional higher-rank polymorphic*
type inference, which was previously studied mostly in the context of functional
programming. However, existing type inference implementations lack solid
theoretical foundations when dealing with non-structural subtyping and
intersection and union types, which were not studied before.

In this paper, we study bidirectional higher-rank polymorphic type inference
algorithms with intersection and union types. We introduce both a bidirectional
specification and algorithmic versions of the type system. We first study a type
inference algorithm that has good theoretical properties: it is sound, complete,
and decidable with respect to the corresponding bidirectional specification.
This is helpful to identify a class of types that can always be inferred. We
also explore algorithmic variants that are sound but not necessarily complete.
These variants incorporate practical features, such as handling records, which
align with real-world implementations. These variants enable inference for a
broader range of types, enhancing the expressiveness of the type systems. Our
findings provide insights for improving current implementations and inspire the
design of novel type inference algorithms. To ensure rigor, all results are
formalized in the Coq proof assistant.


### QuickSub: Efficient Iso-Recursive Subtyping

Many programming languages need to check whether two recursive types are in a
subtyping relation. Traditionally recursive types are modelled in two different
ways: equi- or iso- recursive types. While efficient algorithms for subtyping
equi-recursive types are well studied for simple type systems, efficient
algorithms for iso-recursive subtyping remain understudied. In this paper we
present QuickSub: an efficient and simple to implement algorithm for
iso-recursive subtyping. QuickSub has the same expressive power as the
well-known iso-recursive Amber rules. The worst case complexity of QuickSub is
*O(nm)*, where *m* is the size of the type and *n* is the number of recursive
binders. However, in practice, the algorithm is nearly linear with the worst
case being hard to reach. Consequently, in many common cases, QuickSub can be
several times faster than alternative algorithms. We validate the efficiency of
QuickSub with an empirical evaluation comparing it to existing equi-recursive
and iso-recursive subtyping algorithms. We prove the correctness of the
algorithm and formalize a simple calculus with recursive subtyping and records.
For this calculus we also show how type soundness can be proved using QuickSub.
All the results have been formalized and proved in the Coq proof assistant.