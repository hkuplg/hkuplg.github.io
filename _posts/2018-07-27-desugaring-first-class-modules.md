---
layout:  post
title:   "Desugaring First-class Modules"
authors: "Linus"
date:    2017-12-08 10:00:00 +0800
venue:   "CB 313"
categories: Linus 2018
---
## Abstract
Lambda-I-Sigma is a core calculus that incorporates necessary language
features to encode module systems, including dependent types, strong
dependent sums and subtyping. In this talk, we present how to build a
surface language with first-class modules on top of
Lambda-I-Sigma. The core language is extended with existential opening
to deal with "boxed" types introduced by second projection. The
translation process is type-directed and proved to be sound. A live
demonstration will be presented to show type-checking of the surface
language.
