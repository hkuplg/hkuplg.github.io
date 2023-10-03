---
layout:  post
title:   Extending Higher-rank Polymorphism to Intersection and Union Type
authors: Shengyi
date:    2023-10-04 10:10:00 +0800
venue:   CB308
---

Jimmy's worklist approach was very succesful in formalizing type inference algorithms
for higher-rank polymorphism with implicit predicative instantiation. However, the old
algorithm relies on the an important property that "subtyping between monotypes implies
equality of monotypes" to work. In this talk, we will explore a system that extends HRP
to first class intersection and union types. This system loses the above property and thus 
requires new algorithm framework. We will discuss several challenges in designing both 
declarative and algorithmic rules and revisit some lessons learned in the Coq formalization.
