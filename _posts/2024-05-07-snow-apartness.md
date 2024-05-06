---
layout:  post
title:   Liberating the Merge Operator with Type Apartness and Guarded Upcasting
authors: Snow
date:    2024-05-07 10:10:00 +0800
venue:   CB308
---

In this talk, I will present an ongoing collaborative work with Han Xu. Our new calculus extends the design of disjoint intersection types and enables overloading on function argument types.

Disjoint intersection types were introduced to eliminate ambiguity and ensure well-behaved semantics for the flexible merge operator. However, they can be overly constraining. For example, functions with the same return types are not allowed to be composed. To tackle this problem, the Fbow calculus proposed by Rioux et al. offers a solution by decomposing disjointness into dual type notions. Our work takes another approach. We introduce type apartness as a relaxed version of type disjointness, which does not guarantee the coherence of upcasting. Correspondingly, we introduce guarded upcasting, which is a restricted version of subtyping. Ultimately, we aim to develop a system accommodating intersection types, subtyping distributive laws, union types, and polymorphic types. The proposed calculus prioritizes type safety and determinism, employing type normalization procedures to prevent unwanted duplication.

This talk will also be available online. The Zoom link will be shared on Slack tomorrow.
