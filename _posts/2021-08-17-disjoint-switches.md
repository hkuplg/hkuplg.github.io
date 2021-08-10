---
layout:  post
title:   "Union Types with Disjoint Switches"
authors: "Baber Rehman"
date:    2021-08-17 10:00:00 +0800
venue:   "CB 313"
categories: seminar
---

## Abstract

Union types allow expressing terms with alternative types, and are nowadays a common feature in many
modern programming languages. This work investigates a formulation of union types, inspired by the Ceylon
programming language, with an elimination construct that enables case analysis (or switches) on types.
The interesting aspect of such construct is that each clause must operate on disjoint types. By using such
elimination construct, it is possible to ensure exhaustiveness (i.e. all possible cases are handled), and that none
of the cases overlap. In turn, this means that the order of the cases does not matter and reordering the cases
has no impact on the semantics, which can aid program understanding and refactoring. While implemented
in the Ceylon language, such construct with disjoint switches has not been formally studied in the research
literature, although a related notion of disjointness has been studied in the context of disjoint intersection types.
We study union types with disjoint switches formally and in a language independent way.
