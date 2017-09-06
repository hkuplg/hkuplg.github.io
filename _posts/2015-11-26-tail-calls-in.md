--- 
layout:  post 
title:   "Tail Calls in the JVM with Imperative Functional Objects"
authors: "Tomas"
date:    2015-11-26 14:30:00 +0800
venue:   "CB 313"
categories: Tomas Seminar 2015
--- 
## Abstract

This talk presents FCore: a JVM implementation of System F with
support for full tail-call elimination (TCE). Our compilation
technique for FCore is innovative in two respects: it uses a new
representation for first-class functions called imperative functional
objects; and it provides a way to do TCE on the JVM using constant
space. Unlike conventional TCE techniques on the JVM, allocated
function objects are reused in chains of tail calls. Thus, programs
written in FCore can use idiomatic functional programming styles,
relying on TCE, and perform well without worrying about the JVM
limitations. Our empirical results show that programs which use tail
calls can run in constant space and with low execution time overhead
when compiled with FCore.

