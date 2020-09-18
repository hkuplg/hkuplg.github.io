--- 
layout:  post 
title:   "Higher-rank Polymophism on a Dependent Type System"
authors: "XUE Alvin Mingqi"
date:    2020-06-30
venue:   "CB308"
categories: Alvin 2020
--- 

## Abstract

The higher-rank polymorphism is a language feature that allows polymorphic
types to appear in arbitrary position of a type, not just top-level.
Joshua Dunfield and @Jimmy Zhao have investigated the local type inference of
higher-rank polymorphism on a non-dependent type system that resembles system-F,
where they made use of subtyping as a tool to formalize a "more-general"
relation between polymorphic and monomophic types.

In my very first seminar in the group, I will be introducing my current research
progress of generalizing such subtyping relation to a dependent type system.
We are using the "Unified Subtyping" developed by @Linus Yang to untie the
potential mutual dependency between typing and subtyping for a dependently-typed
language, which was a issue that introduced major complexity in other previous
works with subtyping and dependent types.

Hopefully we will develop a reasonable metatheory for the system :D.
