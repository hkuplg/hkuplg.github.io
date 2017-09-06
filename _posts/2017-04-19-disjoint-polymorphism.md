--- 
layout:  post 
title:   "Disjoint Polymorphism"
authors:  "Joao"
time:     2017-04-19 10:00:00
venue:   "CB 328"
categories: "Joao" Seminar 2017
--- 
## Abstract

The combination of intersection types, a merge operator and parametric
polymorphism enables important applications for programming. However, such
combination makes it hard to achieve the desirable property of a coherent
semantics: all valid reductions for the same expression should have the same
value. Recent work proposed disjoint intersections types as a means to
ensure
coherence in a simply typed setting. However, the addition of parametric
polymorphism was not studied. This paper presents Fi: a calculus with
disjoint
intersection types, a variant of parametric polymorphism and a merge
operator.
Fi is both typesafe and coherent. The key difficulty in adding polymorphism
is
that, when a type variable occurs in an intersection type, it is not
statically
known whether the instantiated type will be disjoint to other components of
the
intersection. To address this problem we propose disjoint polymorphism: a
constrained form of parametric polymorphism, which allows disjointness
constraints for type variables. With disjoint polymorphism the calculus
remains
very flexible in terms of programs that can be written, while retaining
coherence.


