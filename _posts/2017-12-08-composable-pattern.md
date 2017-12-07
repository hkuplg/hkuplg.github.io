---
layout:  post
title:   "Composable pattern matching with visitors"
authors: "Weixin"
date:    2017-12-08 10:00:00 +0800
venue:   "CB 313"
categories: Weixin 2017
---
## Abstract
Very often operations used in compilers, interpreters or program analysis, require extensive analysis on a complex abstract syntax tree (AST) structure. 
Pattern matching, an important feature of functional languages, makes the analysis and minipulatation on an AST concise.
However, existing approaches to pattern matching are not satisfactory. To our best knowledge, none of them satisfies four important properties, namely conciseness, 
totality, extensibility and composability. In this talk, I will present a new pattern matching technique that (partially) meets all these properties. 
The idea is to combine extensible visitors with case classes in Scala. As a case study, we refactor types and programming languages interpreters with this approach.  
The results show that our approach significantly reduces the SLOC and outperforms my previous work on EVF. 
