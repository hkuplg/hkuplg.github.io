---
layout:  post
title:   "Taming Intersection Types and the Merge Operator"
authors: "Snow"
date:    2022-11-23 17:00:00 +0800
venue:   "CB308"
categories: "seminar"
---
## Abstract

For modern programming languages, a systematic approach for
establishing usability and reliability is to first have a formalized
and verified core language guarded by a type system.  In this talk, I
will present a type-directed operational semantics (TDOS) approach to
model disjoint intersection types, and studies three calculi Lambdai,
Lambdai+, and  Fi+, serving as a new foundation for Compositional
Programming.

Compositional Programming is a recently proposed programming style.
Its prototype language CP supports multiple inheritance in a type-safe
way and provides simple solutions to modularity problems that are hard
for conventional object-oriented programming and functional
programming languages.  At the core of CP is Fi+, a polymorphic
calculus that supports a symmetric merge operator with subtyping.  The
merge operator generalizes record concatenation to any type, enabling
expressive forms of object composition.

Due to its flexibility and ambiguity, the merge operator lacks a
satisfying direct operational semantics.  Prior systems usually define
the runtime semantics indirectly by elaborating the source expressions
into a target language.  In contrast, the TDOS approach gives a
semantics to Fi+ directly.  Besides being deterministic and type
sound, the new calculus supports additional features such as recursion
and impredicative polymorphism.

As an essential part of the TDOS design, we show a novel algorithm for
the subtyping of intersection types with distributive laws.  In this
formulation, types that decompose into two smaller parts are
characterized by splittable types.  This allows a simple proof of
transitivity and the modular addition of distributivity rules without
pre-processing on types.  We then extend this idea to union types and
present an algorithmic formulation of subtyping based on the minimal
relevant logic B+.
