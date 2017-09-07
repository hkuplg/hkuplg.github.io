--- 
layout:  post 
title:   "Modular Unfolds"
authors: "Haoyuan"
date:    2017-09-06 10:00:00 +0800
venue:   "CB 313"
categories: Haoyuan 2017
--- 
## Abstract

Object Algebras allow programmers to write abstract syntax trees (ASTs) and
algebras (folds) in a modular way. The idea of modular folds was already
well
studied in functional programming, including the famous paper "Data types a
la
carte". By encoding ASTs into small composable functors, the operations that
consume structures, namely folds, can be defined in an extensible way.

Whereas the dual operation that generates structures, which we call
coalgebras
or unfolds, has not drawn much attention as it deserves. In the talk I will
present a natural and practical pattern of writing modular unfolds. There
will
be some intuitive examples and larger case studies.


