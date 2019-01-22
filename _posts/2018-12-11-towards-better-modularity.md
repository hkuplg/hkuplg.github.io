---
layout:  post
title:   "Towards Better Modularity in Multiple Inheritance"
authors: "Grace"
date:    2018-12-11 10:00:00 +0800
venue:   "CB 313"
categories: Grace 2018
---
## Abstract

Multiple inheritance is good but hard to implement. Why is multiple inheritance hard? There are various reasons,
1)member conflicts.
2)diamond problem
3)initialization
,etc.

In this talk, I will summarize the projects I've done in my PhD study by discussing three specific problems I encountered and give solutions to these problems:
1. I will show how to solve the expression problem by a simple language feature: covariant return types. 
2. I will present Classless Java, a formal calculus for an instantiation of interface-based programming in Java. Interfaces are used to achieve modularity and extensibility in multiple inheritance.
3. I will present FHJ: a formal model for hierarchical dispatching and overriding. This work solves the problem of "unintentional method conflicts" problem in multiple inheritance.

At last, I will sum up and briefly talks about the ongoing/future work FHJ+.
