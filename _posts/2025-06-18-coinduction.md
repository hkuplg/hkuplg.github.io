---
layout:  post
title:   New Techniques for Coinduction Formalizations
authors: Litao
date:    2025-06-18 10:10:00 GMT+8
venue:   CB308
---

Coinduction is an essential principle for reasoning about infinite data
structures and cyclic computations, such as streams. However, its
direct implementation in proof assistants like Coq relies on a strict syntactic
"guardedness" condition to ensure productivity. This syntactic check, while
effective, is often too restrictive, rejecting many semantically productive
definitions and complicating proofs by preventing the use of auxiliary lemmas
within coinductive arguments.

This problem session presents a more powerful approach to formalizing
coinduction by shifting from syntactic checks to a semantic foundation based on
greatest fixed points (gfp) of monotone bisimulation operators. We leverage the
"Tower Induction" principle, which defines bisimilarity—the canonical equality
for coinductive types—as the limit of an approximation chain. This framework
enables powerful "up-to" techniques, allowing us to seamlessly rewrite based on
congruences and apply lemmas in coinductive proofs, overcoming the limitations
of the native guard condition.

To demonstrate the power of this method, we present its application to the
metatheory of equi-recursive types. As a starting point, we prove the
equivalence of two equi-recursive equality definitions in Coq, one based on the
standard coinductive definition and the other on a model of infinite trees. This
was hard to formalize in Coq using standard `cofix` tactic due to guardedness
limitations. The talk concludes by discussing how these techniques might be
extended to mechanizing the metatheory of more expressive type systems and
tackling open formalization problems in recursive subtyping.

References:
- The `coinduction` library in Coq: https://github.com/damien-pous/coinduction
- The EPIT 2025 spring school lecture on coinduction: https://github.com/damien-pous/epit25/