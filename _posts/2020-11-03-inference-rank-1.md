--- 
layout:  post 
title:   "Type Inference with Rank-1 Restriction"
authors: "Jimmy"
date:    2020-11-03 10:00:00 +0800
venue:   "CB308"
categories: Jimmy 2020
--- 
## Abstract

Type Inference plays an important role in modern programming language design, as the functional programming style is accepted by more and more programmers.
Unfortunately, full type inference on System F is undecidable, being an impredicative and higher-rank system.
In practice, predicativity and rank-1 are reasonable restrictions that are adopted by most of the programming languages (the ML family, Haskell, etc.).

Our previous work (ICFP 2019) proposes an algorithm that completely infers types in a predicative higher-rank type system without the support to the top type (object-oriented subtyping).
In this seminar talk, I will introduce a new predicative subtyping algorithm that supports the top type with the rank-1 restriction.
