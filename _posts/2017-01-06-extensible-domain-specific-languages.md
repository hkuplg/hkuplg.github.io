--- 
layout:  post 
title:   "Extensible Domain-Specific Languages in Object-Oriented Programming"
authors: "Weixin"
date:    2017-01-06 10:30:00 +0800
venue:   "CB 313"
categories: Weixin 2017
--- 
## Abstract

Domain-specific languages (DSLs) are now ubiquitous. New DSLs are needed and
existing DSLs are evolving all the time. However, creating and maintaining
DSLs
is hard, requiring a lot of engineering effort and expertise knowledge. One
way
to address these difficulties is to have language components with high
reusability and extensibility. DSLs, or programming languages in general,
share
a lot of features. Syntactic modularization techniques based on
meta-programming
and code generation have been used for component reuse. However, more
semantic
aspects of modularity, such as the ability to do separate compilation and
modular type-checking, are typically missing.

We argue that object-oriented languages, equipped with powerful semantic
modularization techniques, are suitable for developing extensible DSLs. In
the
first part of this talk, we introduce EVF, an extensible and expressive Java
Visitor framework, for facilitating external DSL development. To illustrate
the
applicability of EVF we conduct a case study, which refactors a large
number of
non-modular interpreters from the “Types and Programming Languages” book.
In the
second part of the talk, we show the close relationship between shallow
embeddings and OOP and how OOP improves the modularity of internal DSLs.


