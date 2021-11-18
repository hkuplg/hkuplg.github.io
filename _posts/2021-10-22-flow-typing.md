---
layout:  post
title:   "Revisiting Occurrence Typing: Global Context and Disjointness"
authors: "Baber"
date:    2021-10-22 10:00:00 +0800
venue:   "CB 313"
categories: problem_session
---

## Abstract

Flow typing or occurrence typing specializes the type of an expression
in a type-case analysis. It has been implemented in some modern programming
languages including Ceylon, Typescript, Flow and Racket etc.
Flow typing has various practical applications such as safe type-casting
and detecting null deference at compile time.
In this talk we will revisit occurrence typing to specialize the
type of expressions in global context. We will further discuss
the relationship of occurrence typing with disjoint switches.