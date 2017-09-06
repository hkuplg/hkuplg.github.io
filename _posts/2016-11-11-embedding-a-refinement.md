--- 
layout:  post 
title:   "Embedding a Refinement Calculus in Coq"
authors:  "John"
time:     2016-11-11 10:30:00
venue:   "CB 313"
categories: "John" Seminar 2016
--- 
## Abstract

Dependently-typed languages are commonly used in the area of formal methods,
where the correctness imposed by the type-system plays a central role in the
certification of software. Examples of such uses include formalising
programming
languages; validating software protocols; certifying the (partial)
correctness
of programs; or — perhaps more generally — theorem proving.

In this talk we will see how we can reason and derive (impure) imperative
programs from their specifications, using a dependently-typed language like
Coq.
We will use a refinement calculus as the theoretical framework for program
derivation, and Coq as the implementation language by defining an embedded
domain specific language (EDSL). The resulting EDSL will allows us to
construct
executable programs by repeatedly applying refinement rules to a given
specification.


