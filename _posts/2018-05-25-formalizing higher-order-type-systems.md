---
layout:  post
title:   "Formalizing higher-order type systems without output contexts"
authors: "Jimmy"
date:    2018-05-25 10:00:00 +0800
venue:   "CB 313"
categories: Jimmy 2018
---
## Abstract
After many attempts for a simple enough formalization for Dunfield's higher-order type system, we finally found a proper way to do so. This talk will go through the technical highlights for such a formalization. The judgment-list form is still empolyed, but we use a more flexible form of contexts, which enables us to deal with variable scopings more precisely. Judgments with output types, such as type inference, are encoded using the continuation passing style, so that variable bindings no longer cause problems. Though the proofs are under development, this system already overcome most of the concerns for the subtyping formalization.
