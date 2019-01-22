---
layout:  post
title:   "Coercion Quantification"
authors: "Ningning"
date:    2018-10-05 10:00:00 +0800
venue:   "CB 313"
categories: Ningning 2018
---
## Abstract
Dependent Haskell has been desired in the community of Haskell
programmers for a long time. Our goal of this project is to make the
core language of Haskell, known as System FC, dependently typed, as
steps are taken towards dependent Haskell.
This is a working-in-progress project. As a small step towards our
final goal, the focus of this talk is on coercion quantification.
Coercion quantification is necessary to support homogeneous equality,
which simplifies the core and is important for meta-theories of
dependently typed core.
Coercion quantification is interesting for both people working in core
and for Haskell users. For GHC hackers, the patch to core
formalization is worth attention. Adding coercion quantification
involves refactor to lots of files in the compilation pipeline and
introduces several subtleties. For Haskell users, coercion
quantification opens up new questions to the design space in source
Haskell, which requires non-trivial extension of the solver. We would
want Haskell users to answer if this feature is ever desired in their
development.
In this talk, we will share the high-level story-line of the
dependently typed core, our low-level progress in implementing
coercion quantification, as well as the involving design space, and
seek feedbacks from the broader community.
