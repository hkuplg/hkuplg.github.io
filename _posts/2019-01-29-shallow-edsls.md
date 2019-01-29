---
layout:  post
title:   "Shallow EDSLs and Object-Oriented Programming: Beyond Simple Compositionality"
authors: "Weixin"
date:    2019-01-29 10:00:00 +0800
venue:   "CB 313"
categories: Weixin 2019
---
## Abstract
Embedded Domain-Specific Languages (EDSLs) are a common and widely used approach to DSLs in various languages, including Haskell and Scala. There are two main implementation techniques for EDSLs: shallow embeddings and deep embeddings. Shallow embeddings are quite simple, but they have been criticized in the past for being quite limited in terms of modularity and reuse. In particular, it is often argued that supporting multiple DSL interpretations in shallow embeddings is difficult.
In this talk, we argue that shallow EDSLs and Object-Oriented Programming (OOP) are closely related. Gibbons and Wu already discussed the relationship between shallow EDSLs and procedural abstraction, while Cook discussed the connection between procedural abstraction and OOP. We make the transitive step by connecting shallow EDSLs directly to OOP via procedural abstraction. The knowledge about this relationship enables us to improve on implementation techniques for EDSLs.
In this talk, we argue that common OOP mechanisms (including inheritance, subtyping, and type-refinement) increase the modularity and reuse of shallow EDSLs when compared to classical procedural abstraction by enabling a simple way to express multiple, possibly dependent, interpretations.
We make our arguments by using Gibbons and Wu’s examples, where procedural abstraction is used in Haskell to model a simple shallow EDSL. We recode that EDSL in Scala and with an improved OO-inspired Haskell encoding. We further illustrate our approach with a case study on refactoring a deep external SQL DSL implementation to make it more modular, shallow, and embedded.
