---
layout:  post
title:   Two Practice Talks for OOPSLA
authors: Chen, Wenjia
date:    2023-10-11 10:10:00 +0800
venue:   CB308
---



### Greedy Implicit Bounded Quantification

<https://2023.splashcon.org/details/splash-2023-oopsla/105/Greedy-Implicit-Bounded-Quantification>

Mainstream object-oriented programming languages such as Java, Scala, C#, or TypeScript have polymorphic type systems with subtyping and bounded quantification. Bounded quantification, despite being a pervasive and widely used feature, has attracted little research work on type-inference algorithms to support it. A notable exception is local type inference, which is the basis of most current implementations of type inference for mainstream languages. However, support for bounded quantification in local type inference has important restrictions, and its non-algorithmic specification is complex.

In this paper, we present a variant of kernel $F_{\le}$, which is the canonical calculus with bounded quantification, with implicit polymorphism. Our variant, called $F_{\le}^b$, comes with a declarative and an algorithmic formulation of the type system. The declarative type system is based on previous work on bidirectional typing for predicative higher-rank polymorphism and a greedy approach to implicit instantiation. This allows for a clear declarative specification where programs require few type annotations and enables implicit polymorphism where applications omit type parameters. Just as local type inference, explicit type applications are also available in $F_{\le}^b$ if desired. This is useful to deal with impredicative instantiations, which would not be allowed otherwise in $F_{\le}^b$. Due to the support for impredicative instantiations, we can obtain a completeness result with respect to kernel $F_{\le}$, showing that all the well-typed kernel $F_{\le}$ programs can type-check in $F_{\le}^b$. The corresponding algorithmic version of the type system is shown to be sound, complete, and decidable. All the results have been mechanically formalized in the Abella theorem prover.


### A Gradual Probabilistic Lambda Calculus

<https://2023.splashcon.org/details/splash-2023-oopsla/10/A-Gradual-Probabilistic-Lambda-Calculus>

Probabilistic programming languages have recently gained a lot of attention, in particular due to their applications in domains such as machine learning and differential privacy. To establish invariants of interest, many such languages include some form of static checking in the form of type systems. However, adopting such a type discipline can be cumbersome or overly conservative.


Gradual typing addresses this problem by supporting a smooth transition between static and dynamic checking, and has been successfully applied for languages with different constructs and type abstractions. Nevertheless, its benefits have never been explored in the context of probabilistic languages.
In this work, we present and formalize GPLC, a gradual source probabilistic lambda calculus. GPLC includes a binary probabilistic choice operator and allows programmers to gradually introduce/remove static type–and probability–annotations. The static semantics of GPLC heavily relies on the notion of probabilistic couplings, as required for defining several relations, such as consistency, precision, and consistent transitivity. The dynamic semantics of GPLC is given via elaboration to the target language TPLC, which features a distribution-based semantics interpreting programs as probability distributions over final values. Regarding the language metatheory, we establish that TPLC–and therefore also GPLC–is type safe and satisfies two of the so-called refined criteria for gradual languages, namely, that it is a conservative extension of a fully static variant and that it satisfies the gradual guarantee, behaving smoothly with respect to type precision.
