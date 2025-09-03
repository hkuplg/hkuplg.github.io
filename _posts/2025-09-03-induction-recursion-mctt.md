---
layout:  post
title:   Induction-recursion, Impredicativity and a New Way to Formalize MLTT in Rocq
authors: Qianyong
date:    2025-09-03 10:00:00 GMT+8
venue:   CB313
---

This <del>no-</del>problem session is essentially a reading report for paper [*McTT: A Verified Kernel for a Proof Assistant*](https://doi.org/10.1145/3747511).
I will introduce induction-recursion, which is unsupported by Rocq, and its usage in previous NbE-based formalizations of MLTT.
Then I'll discuss the technique proposed in the paper to workaround this limitation by taking advantage of the impredicativity of the `Prop` sort.

<span style="background-color:#555; color: #555; border: 1px solid #555;">I didn't know Shengyi is working on this project until the seminar.</span>
