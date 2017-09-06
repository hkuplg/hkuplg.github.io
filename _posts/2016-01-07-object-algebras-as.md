--- 
layout:  post 
title:   "Object Algebras as Visitors"
authors: "Weixin"
date:    2016-01-07 14:00:00 +0800
venue:   "CB 308"
categories: Weixin Seminar 2016
--- 
## Abstract

Object Algebras are a design pattern for building extensible software,
which are essentially an implementation of internal visitors.
Internal visitors, however, are inefficient (even impossible) to
define certain algebras since it fixes the traversal pattern to be
bottom-up.  External visitors, on the other hand, adopts top-down
traversals are better suited for such algebras.

In this talk, I will first relate Object Algebras to the VISITOR
pattern and introduce a generalized encoding of Object Algebras that
could be instantiated as either internal or external visitors while
retaining extensibility.  Then, I will present the Free framework we
developed, which generates the infrastructure to ease working with
generalized algebras.  Last, I will show the case study we conducted
for illustrating the strength of our framework, where most of the code
from the book "Types and Programming Languages" are rewritten in a
modular way.

