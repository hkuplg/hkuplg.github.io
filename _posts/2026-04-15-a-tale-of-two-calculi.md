--- 
layout:  post 
title:   A Tale of Two Calculi
authors: Yicong Luo
date:    2026-04-15 09:30:00 +0800
venue:   CB308
--- 

> Note: originally planned on 2026-04-01 ...

It was the best of types, it was the worst of runtimes, it was the age of calculi, it was the age of mechanization, it was the epoch of prototypes, it was the epoch of regret. In the well-trodden tradition of programming languages research, one begins with the earnest scribbling of a calculus; proceeds to its agonizing mechanization with a proof assistant of distinctly Victorian sensibilities; and concludes with the faithful translation into a prototype in a purely functional language whose LSP cheerfully devours every last byte of virtual memory.

This talk proposes, in the gentlest possible way, that the passage between these two great cities—the **City of Proof** and the **City of Programs**—is surprisingly negotiable. Rather than shuttling endlessly between them, we may **Lean** toward one and find, to our mild surprise, that the other has been there all along.

To illustrate this shortcut, we present a singular construction: a complete pipeline for the simply typed lambda calculus — spanning parser, type checker, evaluator, and of course, the formalization of metatheory.
