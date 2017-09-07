--- 
layout:  post 
title:   "Object Algebras in Our Language"
authors: "Haoyuan"
date:    2015-02-12 14:00:00 +0800
venue:   "CB 313"
categories: Haoyuan 2015
--- 
## Abstract

This is like a tutorial implementation of object algebras in our
  language. Currently our compiler has no support for simple syntax of
  object algebras, so we have to design types by ourselves using
  simple constructors. In this talk, I'll show you how to implement
  algebra interfaces, queries and transformations, and how it works
  while still holding extensibility by using intersection types. An
  advanced feature is to have visitors for data structures, so as to
  save a lot of work in client code. Some more complicated examples
  will be available then, together with some discussions on pros and
  cons of programming in such a style, and prospects of designing
  syntactic sugar for algebras.

