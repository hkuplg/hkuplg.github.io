--- 
layout:  post 
title:   Two practice talks for OOPSLA
authors: Litao, Jinhao
date:    2024-09-11 10:10:00 GMT+8
venue:   CB308
--- 


### A Case for First-Class Environments 

Formalizations of programming languages typically adopt the substitution model from the lambda calculus. However, substitution creates notorious complications for reasoning and implementation. Furthermore, it is disconnected from practical implementations, which normally adopt environments and closures.

In this paper we advocate for formalizing programming languages using a novel style of small-step environment-based semantics, which avoids substitution and is closer to implementations. We present a call-by-value statically typed calculus, called λE, using our small-step environment semantics. With our alternative environment semantics programming language constructs for first-class environments arise naturally, without creating significant additional complexity. Therefore, λE also adopts first-class environments, adding expressive power that is not available in conventional lambda calculi. λE is a conservative extension of the call-by-value Simply Typed Lambda Calculus (STLC), and employs de Bruijn indices for its formalization, which fit naturally with the environment-based semantics. Reasoning about λE is simple, and in many cases simpler than reasoning about the traditional STLC. We show an abstract machine that implements the semantics of λE, and has an easy correctness proof. We also extend λE with references. We show that λE can model a simple form of first-class modules, and suggest using first-class environments as an alternative to objects for modelling capabilities. All technical results are formalized in the Coq proof assistant. In summary, our work shows that the small-step environment semantics that we adopt has three main and orthogonal benefits: 1) it simplifies the notorious binding problem in formalizations and proof assistants; 2) it is closer to implementations; and 3) additional expressive power is obtained from first-class environments almost for free.


### Full Iso-recursive Types

There are two well-known formulations of recursive types: iso-recursive and equi-recursive types. Abadi and Fiore [1996] have shown that iso- and equi-recursive types have the same expressive power. However, their encoding of equi-recursive types in terms of iso-recursive types requires explicit coercions. These coercions come with significant additional computational overhead, and complicate reasoning about the equivalence of the two formulations of recursive types.

This paper proposes a generalization of iso-recursive types called full iso-recursive types. Full iso-recursive types allow encoding all programs with equi-recursive types without computational overhead. Instead of explicit term coercions, all type transformations are captured by computationally irrelevant casts, which can be erased at runtime without affecting the semantics of the program. Consequently, reasoning about the equivalence between the two approaches can be greatly simplified. We present a calculus called $\lambda^{\mu}{Fi}$, which extends the simply typed lambda calculus (STLC) with full iso-recursive types. The $\lambda^{\mu}{Fi}$ calculus is proved to be type sound, and shown to have the same expressive power as a calculus with equi-recursive types. We also extend our results to subtyping, and show that equi-recursive subtyping can be expressed in terms of iso-recursive subtyping with cast operators.