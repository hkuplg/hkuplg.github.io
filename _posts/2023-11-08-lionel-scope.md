--- 
layout:  post 
title:   A Type System for Scope Safety
authors: Lionel Parreaux
date:    2023-11-08 10:10:00 +0800
venue:   CB308
--- 

Many programming idioms rely on some form of stack-based reasoning, whereby program entities are only valid within some specific scopes, which are lexically-delimited regions of the program. However, general-purpose programming languages rarely allow this information to be reflected on the type level. Recently, several approaches were proposed to address this limitation, such as Rust’s lifetime regions, Scala’s Capture Types, as well as Reachability Types and Second-Class Values. But these approaches are either cumbersome or restrictive and lacking in expressiveness. In this talk, I propose a simple polymorphic type-and-effect system to statically restrict the use of scope-delimited values, which is being prototyped as part of the MLscript programming language. Our approach integrates well with MLscript’s constraint-based type inference, meaning that few type annotations need to be provided. Moreover, it has a wide range of applications where scope safety is crucial, including first-class polymorphism, metaprogramming, effect handlers, stack-based memory management, and mutable state encapsulation.