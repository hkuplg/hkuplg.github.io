---
layout:  post
title:   "Unified Subtyping with Strong Dependent Pairs"
authors: "Linus"
date:    2018-05-18 10:00:00 +0800 
venue:   "CB 313"
categories: Linus 2018
---
## Abstract
First-class modules are hard to model in a simple core calculus. They require
many sophisticated language features, including dependent types, strong
dependent pairs and subtyping. It is also non-trivial to combine all these
language features together in a single calculus. We propose an extension to
Lambda-I-Sub, which brings strong dependent pairs to unified subtyping. The main
idea is to use a partial call-by-value reduction in cast operators for more
expressive type conversion. We prove the new calculus enjoys all desired
properties including transitivity and type safety, which could be a promising
theoretic foundation for first-class modules.
