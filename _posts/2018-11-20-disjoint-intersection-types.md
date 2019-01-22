---
layout:  post
title:   "Disjoint intersection types: theory and practice"
authors: "Jeremy"
date:    2018-11-20 10:00:00 +0800
venue:   "CB 313"
categories: Jeremy 2018
---
## Abstract

Intersection types have a long history in programming languages. They were
originally introduced to characterize exactly all strong normalizing lambda
terms. Since then, they have also been employed to express useful programming
languages constructs, such as key aspects of multiple inheritance. Recent years
have seen a proposal of a variant of intersection types called disjoint
intersection types. Disjoint intersection types have great potential to serve as
a foundation for powerful, flexible and yet type-safe OO languages that are easy
to reason about. In my thesis work, I realized the potential by significantly
increasing the expressiveness of disjoint intersection types, culminating in the
first design of first-class traits, supporting, among others, nested
composition, dynamic inheritance, dynamic dispatching and abstract methods.

The talk is composed of three parts. In the first part, I will introduce λᵢ⁺, a
simple calculus with records and disjoint intersection types that supports
nested composition. Of particular importance is its novel proof of coherence
using logical relations. In the second part, I will introduce Fᵢ⁺, combining
disjoint polymorphism with BCD subtyping. The combination is non-trivial and
highly expressive, enabling to model mixins and traits that usually require
sophisticated mechanism. In the final part, I will present SEDEL, the first
design of typed first-class traits, built on top of Fᵢ⁺. I will illustrate the
applicability of SEDEL with several examples, a case study that modularizes
programming interpreters using a highly modular form of visitors.
