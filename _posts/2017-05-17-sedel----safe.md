--- 
layout:  post 
title:   "SEDEL -- Safe and Expressive Delegation-Based Programming"
authors: "Jeremy"
date:    2017-05-17 10:00:00 +0800
venue:   "CB 313"
categories: Jeremy Seminar 2017
--- 
## Abstract

In this talk I present SEDEL: a new polymorphic, statically-typed and
delegation-based object-oriented programming language. The design of SEDEL
follows Cook et al. motto of ``Inheritance is not Subtyping'' and clearly
separates the two notions. Unlike most previous designs for delegation (or
dynamic inheritance) based languages SEDEL is statically typed; has an
expressive polymorphic type system; and it supports a powerful form of
conflict-free multiple dynamic inheritance mechanism called dynamically
composable traits. The design of SEDEL and its type system is based on
previous
work on disjoint intersection types and disjoint polymorphism. This
guarantees
important safety properties, and ensures a high-degree of programming
flexibility. In terms of safety SEDEL's type system provides, not only the
usual
type-safety property, but also coherence. The coherence property ensures
that
the semantics of SEDEL is unambiguous. In particular this property is
useful to
ensure that programs using multiple dynamic inheritance remain free of
conflicts/ambiguities (even when the types of the object parts being
composed
are not statically know). In terms of flexibility, the polymorphic type
system
provides an expressive form of polymorphism and intersection types that can
type-check various delegation-based programs and patterns. We show how the
mechanisms of SEDEL improve extensibility design patterns such as Extensible
Visitors and Object Algebras. Furthermore we show how the high-level OO
mechanisms of SEDEL can be elaborated using a thin-layer of syntactic sugar
into
a core calculus with disjoint intersection types and polymorphism.


