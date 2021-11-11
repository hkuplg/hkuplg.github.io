---
layout:  post
title:   "From Occurrence Typing to Refinement Types"
authors: "Xu Xue"
date:    2021-11-12 10:00:00 +0800
venue:   "CB308"
categories: "problem session"
---

## Abstract

Typed Racket, considered as the most sophisticated type system for Scheme, demonstrates a way how to type check untyped program incrementally, idiomatically, and type safely. The secret behind it is occurrence typing.

I believe Baber has already presented a great introduction to it using examples in a type-driven style. In this problem session, we trace back to the origin of occurrence typing and see how Typed Racket benefits from it without introducing new idioms. And we can further see how refinement types fundamentally subsume it.

Interested audiences may want to skim the introduction in Andrew M. Kent's Ph.D. dissertation "Advanced Logical Type Systems for Untyped Languages" or play with some trivial examples in Liquid Haskell but it's not compulsory.
