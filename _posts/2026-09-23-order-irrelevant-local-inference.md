---
layout:  post
title:   "Order-Irrelevant Local Type Inference via Inference Closures"
authors: "Chen Cui"
date:    2026-09-23 09:00:00 +0800
venue:   "CB308"
---

Local Type Inference (LTI) provides an alternative to global unification for rich polymorphic type systems.
However, LTI techniques often cannot synthesize the types of higher-order arguments.
To handle these arguments, practical implementations use contextual information eagerly, which in turn makes type inference sensitive to argument order.

In this seminar, I will present an order-irrelevant variant of Contextual System F, which supports implicit first-class polymorphism and impredicative instantiation.
When the algorithm lacks enough information to infer a type, it records the unresolved problem and its local environment in an *inference closure*.
Once the surrounding context supplies the missing information, the algorithm resumes inference from the closure.
With inference closures, the algorithm can type many common higher-order programs without annotations and still remain local and free of global unification variables.
