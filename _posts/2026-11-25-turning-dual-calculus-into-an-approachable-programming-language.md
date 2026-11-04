---
layout:  post
title:   "Turning Dual Calculus into an Approachable Programming Language"
authors: "Feng Ding"
date:    2026-11-25 09:30:00 +0800
venue:   "CB308"
---

The λ-calculus corresponds to natural deduction and provides a foundation for functional programming. But it leaves the surrounding evaluation context implicit. Dual calculi,inspired by natural deduction's sibling, sequent calculus, bring that context into the syntax, presenting computation as an interaction between terms and continuations.

This talk presents Mini-Mu, an experimental language built around a variant of the dual calculus. We examine how its computational core makes control flow and evaluation order explicit, and how syntactic sugar makes this explicit structure readable and convenient to program with. Through functions, monads, and objects, we show how several programming idioms can be organized around a common interaction model. If time permits, we will also briefly explore other languages based on variants of the dual calculus.
