--- 
layout:  post 
title:   Higher-rank Polymorphism with Intersection and Union Types
authors: Shengyi Jiang
date:    2024-07-02 10:10:00 GMT+8
venue:   CB308
--- 

  Modern mainstream programming languages, such as TypeScript, Flow,
  and Scala, have polymorphic type systems enriched with intersection
  and union types. These languages implement variants of \emph{bidirectional higher-rank
    polymorphic} type inference, which have been previously studied
  mostly in the context of functional programming. However, existing
  type inference implementations lack solid theoretical
  foundations when dealing with non-structural subtyping and
  intersection and union types.

  In this talk, we present new bidirectional higher-rank polymorphic type
  inference algorithms that address these challenges. We introduce both
  declarative and algorithmic versions of the algorithms. We first study a type
  inference algorithm that has very good theoretical properties: it is sound,
  complete and decidable with respect to the corresponding declarative type
  system. This is helpful to identify a class of types that can always be
  inferred. We also explore algorithmic variants that are sound but not
  necessarily complete. These variants incorporate practical features, such as
  handling records, which align with real-world implementations. These variants
  approach enables inference for a broader range of types, enhancing the
  expressiveness of the type systems. Our findings provide insights for improving current 
  implementations and inspire the design of novel type inference techniques. 
  All properties are formalized in the Coq proof assistant.
