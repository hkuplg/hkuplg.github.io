--- 
layout:  post 
title:   "Classless Java, Continued"
authors: "Yanlin"
date:    2016-01-14 14:00:00 +0800
venue:   "CB 328"
categories: Yanlin Seminar 2016
--- 
## Abstract

In previous talks, we have presented the Expression Problem and our
solution. Later on we presented Classless Java with an annotation
@Obj, which generates factory ‘of’ methods for interfaces as
constructors for classes. And in that talk, we presented that @Obj can
help make our solution to EP nicer (removing boilerplate code). But
when it comes to Expression Problem with family polymorphism
(presented in “The Expression Problem, continued” talk), @Obj is not
enough. In this talk, I will talk briefly review EP with family
polymorphism and Classless Java, use the techniques of @Obj with
Lombok to remove the boilerplate code in our previous solution to EP
in the family polymorphism context. And in turn, the new @Obj become
an extension to the original @Obj (backward compatible), among several
other future extensions.

