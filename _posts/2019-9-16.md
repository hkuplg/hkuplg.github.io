---
layout:  post
Title: Type Inference for Object-Oriented Programming with Higher-Ranked Polymorphism
Date: 2019-09-17 10:00:00
Venue: CB313
Speaker: Jimmy
---
## Abstract
This is the follow-up work of the ICFP 2019 paper "A Mechanical Formalization of Higher-Ranked Polymorphic Type Inference". We now seek the support of object-oriented programming features. Adding the top type allows one to encode object inheritance via parametric polymorphism. Therefore, we extended our type system and subtyping relation. However, the previous "eager" worklist algorithm is not capable of the new system. A lazy alternative is proposed and under exploration.