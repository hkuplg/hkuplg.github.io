---
layout:  post
title:   "On intersection types, from theory to practice"
authors: "Jeremy"
date:    2017-12-01 10:00:00 +0800
venue:   "CB 313"
categories: Jeremy 2017
---
## Abstract


In this talk, I will first give a simple introduction on the history of
intersection types. I will start by describing the well-known results showing
the deep connection between the intersection type systems (CDV and BCD) and
normalization properties. Although BCD is very useful in the study of the
semantics of lambda calculus, it has seen no practical use for being a
programming language. In the second part, I will talk about my recent project
where we significantly extend the expressive power of disjoint intersection
types by adding BCD subtyping. The result calculus is able to express simple
forms of family polymorphism, which we call nested subtyping/composition. The
extension of BCD subtyping is challenging: for obtaining an algorithmic
system and for preserving coherence. I will briefly talk about how we solve
them.
