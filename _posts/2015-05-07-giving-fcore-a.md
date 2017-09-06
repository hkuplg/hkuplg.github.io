--- 
layout:  post 
title:   "Giving FCore a Promotion: by adding a dependently typed core"
authors:  "Jeremy"
time:     2015-05-07 13:45:00
venue:   "CB 313"
categories: "Jeremy" Seminar 2015
--- 
## Abstract

In this talk, we present a concise and compiler-friendly core language
based on Calculus of Construction (COC) that collapses three levels
(terms, types, kinds) into a uniform one, thus making it convenient
for compiler writers, for they only need to write one infrastructure
for all the levels. However, pure COC with general recursion makes
type checking undecidable. To circumvent that, we control the
computation on the type level by introducing generalised
fold/unfold.

We also design a source language with datatypes and pattern matching,
all of which can be elaborated into the new core language. Besides, we
have a working prototype to demonstrate the power of the new
core. Finally we will briefly talk about propositional equality, which
is useful to encode generalized datatypes (GADT).


