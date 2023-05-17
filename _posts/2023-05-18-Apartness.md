--- 
layout:  post 
title:   Apartness for Intersection and Union types
authors: Han Xu
date:    2023-05-18 10:10:00 +0800
venue:   CB308
--- 
Calculi with disjoint intersection types support a symmetric merge operator with subtyping. The merge operator generalizes record concatenation to any type, enabling expressive forms of object composition, and simple solutions to hard modularity problems. Unfortunately, recent calculi with disjoint intersection types poses strong restrictions on functions that forbids us to merge functions with same return types. In this seminar, we proposes a new notion of disjointness, which is apartness, for us to merge more functions. This notion of apartness performs minimal checks on amibiguity. It also cooperates well with union types, and the language built on it is proven to be sound and deterministic.
