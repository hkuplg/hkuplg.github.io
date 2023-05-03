--- 
layout:  post 
title:   Separate Compilation of Compositional Programming
authors: Yaozhu
date:    2023-05-04 10:10:00 +0800
venue:   CB308
--- 

Many programming mechanisms proposed in the past support the ability to merge features from multiple independent units of code into a single unit. Examples include subject-oriented programming, feature-oriented programming, multi-dimensional separation of concerns, virtual classes and family polymorphism, or, more recently, compositional programming. Typically, implementing the merging process employs source-to-source transformations or other mechanisms with limited support for separate compilation.

In this seminar, we present a compiler for the CP language, which implements the idea of compositional programming. CP is a statically typed language that supports not only static merging of features, but also dynamic merging at runtime. In addition, CP enables the development of loosely coupled features and has an expressive form of parametric polymorphism. All those features make the compilation of CP non-trivial, especially if separate compilation is desired. We show how the features in CP can be compiled to languages supporting extensible records or similar mechanisms. Key to this compilation scheme is a mapping from types to record labels that are used to efficiently perform type-based lookups on merges. The main ideas of the compilation scheme are formalized in Coq and proven to be type safe. The concrete implementation of the CP compiler targets JavaScript, where records are modeled via JavaScript objects. We conduct an empirical evaluation through various benchmarks and evaluate the impact of several CP-specific compiler optimizations.
