---
layout:  post
title:   "Design an Operational Semantics for Disjoint Intersection Types"
authors: "Snow"
date:    2018-09-21 10:00:00 +0800
venue:   "CB 313"
categories: Snow 2018
---
## Abstract
All the previous works on disjoint intersection types use elaboration
semantics, transforming intersections to products and eliminating
merged terms by projection on pairs in the target language. This
design choice was initially made be Dunfield in "elaborating
intersection and union types" mainly due to the ambiguity of reducing
a merged term, e,g. e1,,e2 can be reduced to e1 or e2. However, with
the disjoint restriction, we actually prevent such ambiguity. Thurs,
recently we try to design an operational semantics directly with type
information.
