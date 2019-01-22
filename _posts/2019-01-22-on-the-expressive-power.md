---
layout:  post
title:   "On the Expressive Power of Disjoint Polymorphism"
authors: "Ningning"
date:     2019-01-22 10:00:00 +0800
venue:   "CB 313"
categories: Ningning 2019
---
## Abstract
Type systems with disjoint intersection types and disjoint polymorphism have
been recently proposed together with several applications. However the
relationship to other polymorphic type systems is unclear. In particular row
polymorphism (state-of-the art for extensible records) and bounded
quantification (the de facto current standard for languages integrating
subtyping and polymorphism).

This talk shows that Fi+ (a type system with disjoint polymorhism and disjoint
intersection types) can encode programs written in two other calculi: one
calculus with bounded quantification, known as System F<:; and one calculus with
row polymorphism. We show that the elaboration retains key desirable properties,
such as type-safety and decidability of the type system. All the formalizations
have been mechanically formalized in the Coq theorem prover.
