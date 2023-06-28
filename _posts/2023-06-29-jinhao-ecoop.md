--- 
layout:  post 
title:   Dependent Merges and First-Class Environments (Practice Talk for ECOOP)
authors: Jinhao Tan
date:    2023-06-29 10:10:00 +0800
venue:   CB308
--- 

In most programming languages a (runtime) environment stores all the definitions that are available to programmers. 
Typically, environments are a meta-level notion, used only conceptually or internally in the implementation of programming languages. 
Only a few programming languages allow environments to be first-class values, 
which can be manipulated directly in programs. 
Although there is some research on calculi with first-class environments for statically typed programming languages, 
these calculi typically have significant restrictions.

In this paper we propose a statically typed calculus, called Ei, with first-class environments. 
The main novelty of the Ei calculus is its support for first-class environments, 
together with an expressive set of operators that manipulate them. 
Such operators include: reification of the current environment, environment concatenation, 
environment restriction, and reflection mechanisms for running computations under a given environment. 
In Ei any type can act as a context (i.e. an environment type) and contexts are simply types. 
Furthermore, because Ei supports subtyping, there is a natural notion of context subtyping. 
There are two important ideas in Ei that generalize and are inspired by existing notions in the literature. 
The Ei calculus borrows disjoint intersection types and a merge operator, used in Ei to model contexts and environments, 
from the λi calculus. However, unlike the merges in λi, the merges in Ei can depend on previous components of a merge. 
From implicit calculi, the Ei calculus borrows the notion of a query, which allows type-based lookups on environments. 
In particular, queries are key to the ability of Ei to reify the current environment, or some parts of it. 
We prove the determinism and type soundness of Ei, and show that Ei can encode all well-typed λi programs.
