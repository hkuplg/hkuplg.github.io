--- 
layout:  post 
title:   "Applicative Intersection Types"
authors: "Xu Xue"
date:    2021-07-06 10:00:00 +0800
venue:   "CB 313"
categories: seminar
--- 

## Abstract

λi adopts a classical bidirectional type checking and gives rise to many type annotations in the process of function application. In this seminar talk, I will give an introduction to my current research: applicative intersection types, which is basically doing type inference by utilizing a variant of bidirectional type checking: application mode.

Besides removing some unnecessary type annotations from a non-trivial type system with intersection types and merge operator, it's able to encode function overloading in a type-safe manner.

Disclaimer: It's not a talk about applicative functor :p
