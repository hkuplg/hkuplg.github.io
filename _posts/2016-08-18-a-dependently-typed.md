--- 
layout:  post 
title:   "A Dependently Typed Language with Intersection Types"
authors: "Jeremy"
date:    2016-08-18 15:00:00 +0800
venue:   "CB 313"
categories: Jeremy 2016
--- 
## Abstract

In this follow-up talk I will present a dependently typed language with
intersection types. This work is inspired by Dunfield's "Elaborating
intersection and union types". However lifting to dependent types poses new
challenges that are not present in the simply typed setting. We will first
see
what the subtyping rules are like, and how it interacts with the system.
Then I
will present a declarative type system, and later a bidirectional type
system,
which elaborates source expressions to target terms. The bidirectional
system
enjoys several desirable properties, such as type-safe elaboration,
uniqueness
of type-inference, etc. The new calculus is still not complete, as it lacks
coherence. Following Bruno's "Disjoint Intersection Types", we will
investigate
the issue and see how to add disjointness to the system.

