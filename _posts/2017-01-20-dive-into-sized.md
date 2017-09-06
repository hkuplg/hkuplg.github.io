--- 
layout:  post 
title:   "Dive into Sized Types & Copatterns"
authors:  "Jeremy"
date:     2017-01-20 10:30:00
venue:   "CB 313"
categories: "Jeremy" Seminar 2017
--- 
## Abstract

This talk is largely a tutorial on sized types and copatterns, two fairly
recent
new features added in the Agda language. First we will see why type-based
methods for termination based on sized types are superior to various
syntactic
criteria on (co-)recursive definitions, imposed by both Coq and Agda.
Second I
will introduce the concept of copattern matching, dual to pattern matching,
that
allows working with infinite data with ease. Much to my surprise,
coinduction in
Coq is broken: it does not preserve types! Then we will see how copatterns
overcome the subject reduction problem of the Calculus of (Co-)inductive
Constructions. Finally as a large case study, I will try to replicate
Datatype
a la carte in Agda, thanks to Agda's support of sized types.

Jeremy


