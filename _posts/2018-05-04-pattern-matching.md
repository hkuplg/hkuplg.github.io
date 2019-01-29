---
layout:  post
title:   "Pattern Matching in an Open World"
authors: "Weixin"
date:    2018-05-04 10:00:00 +0800
venue:   "CB 328"
categories: Weixin 2018
---
## Abstract
Pattern matching is a pervasive and useful feature in functional programming.
There have been many attempts to bring similar notions to Object-Oriented
Programming (OOP) in the past. However, a key challenge in OOP is how pattern
matching can coexist with the open nature of OOP data structures, while at the
same time guaranteeing other desirable properties for pattern matching.

In this talk, we discuss several desirable properties for pattern matching in an
OOP context, and show how existing approaches are lacking some of these
properties. We argue that the traditional semantics of pattern matching, which
is based on the order of patterns and adopted by many approaches, is in conflict
with the openness of data structures. Therefore we suggest that a more
restricted, top-level pattern matching model, where the order of patterns is
irrelevant is worthwhile considering in an OOP context. To compensate for the
absence of ordered patterns we propose a complementary mechanism for case
analysis with defaults, which can be used when nested and/or multiple case
analysis is needed. To illustrate our points we develop Castor: a
metaprogramming library in Scala that adopts both ideas. Castor generates code
that uses type-safe extensible visitors, and largely removes boilerplate code
typically associated with visitors. We illustrate the applicability of our
approach with a case study modularizing the interpreters in the famous book
“Types and Programming Languages”
