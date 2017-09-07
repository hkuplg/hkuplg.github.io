--- 
layout:  post 
title:   "Classless Java Formalization"
authors: "Haoyuan"
date:    2015-12-10 14:00:00 +0800
venue:   "CB 313"
categories: Haoyuan 2015
--- 
## Abstract

Java 8 introduced default methods, and with the help of multiple
interface inheritance, it seems that traits can be emulated easily in
Java. However some difficulties soon appear that interfaces have no
constructors, and that they don't have state, which motivate the work
behind "Classless Java" (CJ). Yanlin's last seminar talk gave a strong
motivation of the work, and introduced how CJ overcomes those
difficulties.

In my talk, I will continue this topic but focus on another
perspective, which is the formalization of CJ. One contribution of the
work is that a small annotation @Obj is provided to address those
issues in Java interfaces, whereas the implementation of @Obj is based
on a formalization of interfaces, which is CJ: a
FeatherweightJava-style calculus. During the talk, I will introduce
the formalization together with the formal translation by @Obj, and
some theorems it guarantees.

