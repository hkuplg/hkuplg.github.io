---
layout:  post
title:   "A Dependently Typed Calculus with Polymorphic Subtyping"
authors: "Alvin"
date:    2021-06-22 10:00:00 +0800
venue:   "CB 313"
categories: Alvin 2021
---
## Abstract

A polymorphic subtyping relation, which relates more general types to more specific ones, is at the core of many modern functional languages. As those languages start moving towards dependently typed programming a natural question is how can polymorphic subtyping be adapted to such settings.

This paper presents the dependent implicitly polymorphic calculus (λ∀I): a simple dependently typed calculus with polymorphic subtyping. The subtyping relation in λ∀I generalizes the well-known polymorphic subtyping relation by Odersky and Läufer (1996). Because λ∀I is dependently typed, integrating subtyping in the calculus is non-trivial. To overcome many of the issues arising from integrating subtyping with dependent types, the calculus employs unified subtyping, which is a technique that unifies typing and subtyping into a single relation. Moreover, λ∀I employs explicit casts instead of a conversion rule, allowing unrestricted recursion to be naturally supported. We prove various non-trivial results, including type soundness and transitivity of unified subtyping.

λ∀I and all corresponding proofs are mechanized in the Coq theorem prover.
