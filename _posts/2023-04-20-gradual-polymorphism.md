--- 
layout:  post 
title:   "Pragmatic Gradual Polymorphism with References"
authors: Ye Wenjia
date:    2023-04-20 10:10:00 +0800
venue:   CB308
--- 

Gradualizing System F has been widely discussed. A big challenge is to preserve relational parametricity and/or the gradual guarantee. Most past work has focused on the preservation of parametricity, but often without the gradual guarantee. A few recent works satisfy both properties by giving up System F syntax, or with some restrictions and the introduction of sophisticated mechanisms in the dynamic semantics.
While parametricity is important for polymorphic languages, most mainstream languages typically do not satisfy it, for a variety of different reasons. In this paper, we explore the design space of polymorphic languages that satisfy the gradual guarantee, but do not preserve parametricity. When parametricity is not a goal, the design of polymorphic gradual languages can be considerably simplified. Moreover, it becomes easy to add features that are of practical importance, such as mutable references. We present a new gradually typed polymorphic calculus, called λGgpr, with mutable references and with an easy proof of the gradual guarantee. In addition, compared to other gradual polymorphism work, λGgpr is defined using a Type-Directed Operational Semantics (TDOS), which allows the dynamic semantics to be defined directly instead of elaborating to a target cast language. λGgpr and all the proofs in this paper are formalized in Coq.