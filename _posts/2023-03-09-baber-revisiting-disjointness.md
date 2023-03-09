--- 
layout:  post 
title:   "Revisiting Disjoint Polymorphism"
authors: "Baber"
date:    2023-03-09 10:10:00 +0800
venue:   "CB308"
categories: seminar
---

Disjoint switches (Rehman et al. 2022) study a deterministic
type-based elimination of the union types. This work has also
been extended with the advance features of intersection types
and disjoint polymorphism. A complication arises in the disjointness
algorithm when intersection and union types are put together. Therefore,
we redesign the disjointness algorithm based upon the computation of
Least Ordinary Subtypes (LOS). Unfortunately, such an algorithm for the
disjointness results in ad-hoc solution for the disjoint polymorphism.
In particular, a so called ground type restriction on type variable bounds
is essential for the soundness of the disjointness algorithm.

In this talk we will discuss a sound and complete formulation of the
disjointness algorithm with intersection and union types based upon
the union splittable types. The adequacy of the revised disjointness
algorithm lies in the fact that it naturally extends for disjoint
polymorphism without a ground type restriction on the type variable bounds.

Relevant paper:

For those interested in the paper: https://drops.dagstuhl.de/opus/volltexte/2022/16253/

An extension with disjoint polymorphism is in Appendix A.
