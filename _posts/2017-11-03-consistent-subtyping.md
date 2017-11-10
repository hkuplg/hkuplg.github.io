---
layout:  post
title:   "Consistent Subtyping for All"
authors: "Ningning"
date:    2017-11-03 10:00:00 +0800
venue:   "CB 313"
categories: Ningning 2017
---
## Abstract

Consistent subtyping is employed in some gradual type systems to validate type
conversions. The original definition by Siek and Taha serves as a guideline for
designing gradual type systems with subtyping. Polymorphic types a` la System
F also induce a subtyping relation that relates polymorphic types to their
instantiations. However Siek and Taha’s definition is not adequate for
polymorphic subtyping. The first goal of this talk is to propose a
generalization of consistent subtyping that is adequate for polymorphic
subtyping, and subsumes the original definition by Siek and Taha. The new
definition of consistent subtyping provides novel insights with respect to
previous polymorphic gradual type systems, which did not employ consistent
subtyping. The second goal of this talk is to present a gradually typed
calculus for implicit (higher-rank) polymorphism that uses our new notion of
consistent subtyping. We develop both declarative and (bidirectional)
algorithmic versions for the type system. We prove that the new calculus
satisfies all static aspects of the refined criteria for gradual typing, which
are mechanically formalized using the Coq proof assistant.
