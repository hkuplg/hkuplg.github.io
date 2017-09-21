--- 
layout:  post 
title:   "Call-by-value Iso-types"
authors: "Linus"
date:    2017-09-22 10:00:00 +0800
venue:   "CB 313"
categories: Linus 2017
--- 
## Abstract

The Lambda-I calculus features iso-types, a generalization of iso-recursive
types. The original presentation is based on call-by-name weak-head reduction,
uncommonly used by few lazy languages like Haskell. We extend the idea of
iso-types to Pure Type Systems with call-by-value (CBV) semantics which is a
more common evaluation strategy. We impose value restriction on dependent
functions which now can only be applied to values. We also treat variables as
values to allow reasoning on open terms in casts. Type-safety and decidability
of the CBV variant are proved in Coq.
