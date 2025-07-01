---
layout:  post
title:   Distributive Recursive Subtyping via Translation
authors: Litao
date:    2025-07-02 10:10:00 GMT+8
venue:   CB313
---

Subtyping for iso-recursive types has been studied in our group for a long time,
but adding support for distributive properties like `μa.A & μa.B ≤ μa.(A & B)`,
which are useful for modular programming, poses significant challenges for the
current systems such as nominal unfolding rules. 

This talk presents a new approach that defines subtyping not through direct
inference rules, but via a translation. We map recursive types to a simpler
target language based on their "nominal unfoldings" and define subtyping there.
One key innovation is a polarized translation, which is flexible enough to
accommodate the desired distributive rule.

We show this method is complete with respect to a declarative specification of
distributive recursive subtyping. However, the algorithm is not yet sound, and
we present counterexamples involving nested recursion. The talk will discuss the
challenges and our work-in-progress towards a sound and complete algorithmic
system for distributive recursive subtyping.


The talk will be held in person at **CB313**, and is available online via Zoom.
```
Topic: HKUPLG Seminar
Time: Jul 2, 2025 10:00 AM Hong Kong SAR

Join Zoom Meeting
https://hku.zoom.us/j/96777404890?pwd=O5GEjnfMuOnznfyvsjZ3xu5x87otYk.1

Meeting ID: 967 7740 4890
Password: 527183
```
