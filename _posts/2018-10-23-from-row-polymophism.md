---
layout:  post
title:   "From Row Polymorphism to Disjoint Polymorphism"
authors: "Yaoda"
date:    2018-10-23 10:00:00 +0800
venue:   "CB 313"
categories: Yaoda 2018
---
## Abstract
Row polymorphism origins from a type systems for extensible records by Gaster and Jones, then developed by Harper and Pierce. There are three primitive operations: selection, extension and restriction. In our disjoint intersection type, the merge operator can be considered as a generalization of record extension, and selection is also supported natively. For restriction, although it's not common in most type systems, we can replace it by subtyping. Thus we believe that disjoint polymorphism is more expressive than row polymorphism. Therefore, we show how row polymorphism systems is refined and translated to disjoint polymorphism.
