---
layout:  post
title:   "Type-Directed Operational Semantics for Gradual Typing"
authors: "Wenjia"
date:    2021-06-22 10:00:00 +0800
venue:   "CB 313"
categories: Wenjia 2021
---
## Abstract

The semantics of gradually typed languages is typically given indirectly via an elaboration into a cast calculus. This contrasts with more conventional formulations of programming language semantics, where the semantics of a language is given directly using, for instance, an operational semantics. This paper presents a new approach to give the semantics of gradually typed languages directly. We use a recently proposed variant of small-step operational semantics called type-directed operational semantics (TDOS). In TDOS type annotations become operationally relevant and can affect the result of a program. In the context of a gradually typed language, such type annotations are used to trigger type-based conversions on values. We illustrate how to employ TDOS on gradually typed languages using two calculi. The first calculus, called λBg, is inspired by the semantics of the blame calculus, but it has implicit type conversions, enabling it to be used as a gradually typed language. The second calculus, called λBr, explores a different design space in the semantics of gradually typed languages. It uses a so-called blame recovery semantics, which enables eliminating some false positives where blame is raised but normal computation could succeed. For both calculi type safety is proved. Furthermore we show that the semantics of λBg is sound with respect to the semantics of the blame calculus, and that λBr comes with a gradual guarantee. All the results have been mechanically formalized in the Coq theorem prover.
