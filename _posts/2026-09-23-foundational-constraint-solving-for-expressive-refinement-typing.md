---
layout:  post
title:   "Foundational Constraint Solving for Expressive Refinement Typing"
authors: "Jam"
date:    2026-09-23 10:00:00 +0800
venue:   "CB308"
---

SMT-based program verifiers are hamstrung by two problems: expressiveness, because predictable verification
restricts to the boundaries of SMT decidability, and trust, because the solver is a large, unverified artifact whose
soundness bugs may quietly compromise every tool built on it. 

In this talk, we will present Flex, a proof-producing horn-clause solver, that the reduces the trusted base for CHC (Constrained Horn Clauses) solving to the Lean4 kernel alone, and allows using Lean's proof ecosystem to verify low-level system code, via Flux, a refinement type checker for Rust.

The main contributions of this work include:
1) Embed CHCs into Lean4 as Existential Propositions
2) Certifying algorithm for NNF unfolding in CHC to not only synthesize predicates (for acyclic variables) but also, synthesize proofs for rewrites.
3) Predicate abstraction in a foundational setting, using Lean4 definitions as qualifiers and scraping Lean4 code directly for qualifiers. Ongoing work includes adding state of the art Spacer, SMT-based CHC solver, as oracle for predicates.
4) Verifiers. We mechanize two instances of foundational verifiers: an IMP language based on CHC-based Hoare logic and LambdaRK, a lambda calculus with refinement types, whose safety is given via logical relation over refinement types. Finally, we show the backend from Flux, refinement type checker for Rust, to Lean/Flex.
5) Evaluation, the solver is evaluation over set of 880 CHCs produced based on 20k+ Lines of Rust code in the regression suite of Flux.

https://arxiv.org/pdf/2607.12226