--- 
layout:  post 
title:   "When Functional Languages Meet Symbolic Evaluation"
authors: "Weixin"
date:    2015-03-19 13:45:00 +0800
venue:   "CB 313"
categories: Weixin Seminar 2015
--- 
## Abstract

Symbolic evaluation is a means of analysing a program to determine
what inputs cause each part of a program to execute. This technique
has already been widely used in imperative languages for program
analysis, test case generation, verification and other
purposes. However, it is not so popular in the functional language
communities. In fact, functional languages are as good as, if not
better, than imperative languages.

In this talk, I will introduce the key concepts of symbolic
evaluation, such as execution tree and path condition through
examples. Then, I will show you how to encode path conditions into SMT
solvers for the purpose of kicking out infeasible paths. For the last
part of the talk, I will compare symbolic evaluation testing with
random testing and summarise the pros and cons of this technique.

