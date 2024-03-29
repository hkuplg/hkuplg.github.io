---
layout:  post
title:   "Disjoint Switches with Disjoint Functions"
authors: "Baber Rehman"
date:    2022-10-28 10:00:00 +0800
venue:   "CB328"
categories: "problem session"
---

## Abstract

Recent work on disjoint switches for the elimination of untagged union types
doesn't account for the disjointness of multiple functions. This means that
functions with obvious disparate types are not disjoint in current setting.
As a result, a maximum of one function type can appear among multiple branches 
despite of having disparate domain and co-domain of the functions. For example, 
following switch expression doesn't type check:

switch (e):
	Int              => succ e
	(Int -> Bool)    => e 1
	(Bool -> Int)    => e True
	
(Int -> Bool) and (Bool -> Int) aren't differentiated and thus raising an
ambiguity error.

In this problem session we will discuss the feasibility of adding function
disjointness with disjoint switches and allowing the examples as above.
