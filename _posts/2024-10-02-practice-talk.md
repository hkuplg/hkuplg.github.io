--- 
layout:  post 
title:   Yet another practice talk for OOPSLA
authors: Yaozhu
date:    2024-10-02 10:00:00 GMT+8
venue:   CB313
---

### Imperative Compositional Programming: Type Sound Distributive Intersection Subtyping with References via Bidirectional Typing

Compositional programming is a programming paradigm that emphasizes modularity and is implemented in the CP programming language. The foundations for compositional programming are based on a purely functional variant of System F with intersection types, called Fi+, which includes distributivity rules for subtyping.

This paper shows how to extend compositional programming and CP with mutable references, enabling a modular, imperative compositional programming style. A technical obstacle solved in our work is the interaction between distributive intersection subtyping and mutable references. Davies and Pfenning [2000] studied this problem in standard formulations of intersection type systems and argued that, when combined with references, distributive subtyping rules lead to type unsoundness. To recover type soundness, they proposed dropping distributivity rules in subtyping. CP cannot adopt this solution, since it fundamentally relies on distributivity for modularity. Therefore, we revisit the problem and show that, by adopting bidirectional typing, a more lightweight and type sound restriction is possible: we can simply restrict the typing rule for references. This solution retains distributivity and an unrestricted intersection introduction rule. We present a first calculus, based on Davies and Pfenning's work, which illustrates the generality of our solution. Then we present an extension of Fi+ with references, which adopts our restriction and enables imperative compositional programming. We implement an extension of CP with references and show how to model a modular live-variable analysis in CP. Both calculi and their proofs are formalized in the Coq proof assistant.