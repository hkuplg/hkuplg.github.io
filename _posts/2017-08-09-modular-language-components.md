--- 
layout:  post 
title:   "Modular language components with explicit ASTs"
authors: "Li Huang"
date:    2017-08-09 10:00:00 +0800
venue:   "CB 313"
categories: LiHuang Seminar 2017
--- 
## Abstract

In previous talks, we showed how to modularize parsers with Object Algebras.
However, we do not have explicit representation of ASTs with Object
Algebras,
which is desired for language modularization. In this talk we will show how
to
adopt modular external visitors for AST representation. Some enhancements
based
on the original work will be discussed, including support of multiple sorts
and
context propagation. We apply the modular parsing pattern and use
meta-programming to reduce boilerplate code, in order to build handy and
fully
modularized language components. Finally, we will present some results of
our
case study.


