---
layout:  post
title:   "Elaborating Merges to Records: Modeling the Compilation of Fi+ to JavaScript"
authors: "Snow"
date:    2022-11-04 10:10:00 +0800
venue:   "CB308"
categories: "seminar"
---
## Abstract

  CP is a prototype language of the recently proposed Compositional
  Programming paradigm. It is firstly introduced by Zhang, Sun, and
  Oliveira in their TOPLAS 2021 paper Compositional Programming. In
  that work, they implemented an interpreter for CP using Haskell.
  Later, in the OOPSLA 2022 paper Compositional Embeddings of
  Domain-Specific Languages, Sun, Dhandhania, and Oliveira
  reimplemented the CP language as an in-browser interpreter using
  PureScript.  To accelerate program execution in CP, Mr. Sun is now
  optimizing CP's runtime semantics and designing a compiler for CP.
  The key part of the compilation is to translate expressions in Fi+,
  the core calculus of CP, to programs in JavaScript.  Although
  Mr. Sun formalizes the compilation scheme in inference rules, prove
  properties on JavaScript code is hard.  For better understanding of
  the compilation process, we want to abstract it as elaborating Fi+
  to a record calculus, which reflects the important aspects of the
  compilation, e.g., how labels are constructed from types, and can be
  proved to have interesting properties like type safety.  In this
  talk I will present our current design and discuss some problems.
  Any suggestions and comments are welcome!
