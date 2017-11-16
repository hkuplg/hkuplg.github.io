---
layout:  post
title:   "Let Arguments Go into Disjoint Intersection Types"
authors: "Snow"
date:    2017-11-17 10:00:00 +0800
venue:   "CB 313"
categories: Snow 2017
---
## Abstract

In "Disjoint Intersection Types", Oliveira et al. proposed a calculus λ_i with intersection types and a merge operator. This work has been enhanced by Jeremy et al in "Coherent Nested Composition with Disjoint Intersection Types". They presented λ_i^+, which supports nested composition by having the distributivity rules between function/records and intersection types in its subtyping relation. By the subtyping rule (A->B)&(A->C) <: A-> B&C, two functions can be combined and applied together simply via a merge operator. These two calculi are type-safe and coherent. However, like λ_i, the type system of λ_i^+ is based on the traditional bi-directional type checking, which cannot infer a function's type through subtyping relation. To reduce the burden of type annotations, we employ a new variant of bidirectional type-checking proposed by Ningning et al. in "Let Arguments Go First", where the type information flows from arguments to function. 

In this seminar, I am going to present our progress, and share some problems. I am looking forward to your comments and suggestions.
