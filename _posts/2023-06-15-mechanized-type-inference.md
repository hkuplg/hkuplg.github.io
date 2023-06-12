--- 
layout:  post 
title:   No Unification Variable Left Behind - Fully Grounding Type Inference for the HDM System
authors: Roger Bosman
date:    2023-06-15 17:00:00 +0800
venue:   CB328
--- 


The Hindley-Damas-Milner (HDM) system provides polymorphism, a key feature of functional programming languages such as Haskell and OCaml. It does so through a type inference algorithm, whose soundness and completeness have been well-studied and proven both manually (on paper) and mechanically (in a proof assistant). Earlier research has focused on the problem of inferring the type of a top-level expression. Yet, in practice, we also may wish to infer the type of subexpressions, either for the sake of elaboration into an explicitly-typed target language, or for reporting those types back to the programmer. One key difference between these two problems is the treatment of underconstrained types: in the former, unification variables that do not affect the overall type need not be instantiated. However, in the latter, instantiating all unification variables is essential, because unification variables are internal to the algorithm and should not leak into the output.

We present an algorithm for the HDM system that explicitly tracks the scope of all unification variables. In addition to solving the subexpression type reconstruction problem described above, it can be used as a basis for elaboration algorithms, including those that implement elaboration-based features such as type classes. The algorithm implements input and output contexts, as well as the novel concept of full contexts, which significantly simplifies the state-passing of traditional algorithms. The algorithm has been formalised and proven sound and complete using the Coq proof assistant.


This is a guest talk by Roger Bosman, a PhD student of Tom Schrijvers. The talk will be delivered from zoom, and we will set up the camera and mics in CB328.

https://hku.zoom.us/j/92467302923?pwd=REU1QmNWdTFFVGhYbVBMQ2hrUytUZz09

Meeting ID: 924 6730 2923
Password: 286024
