---
layout:  post
title:   "Smart combinators for test data generation"
authors: "Haoyuan"
date:    2018-08-17 10:00:00 +0800
venue:   "CB 313"
categories: Haoyuan 2018
---
## Abstract
Recent years have observed the prosperity of a branch from programming
language area, called test data generation. It is widely used, for
example, in the design of compilers for property-based testing. As a
representative, Quickcheck is a well-known Haskell library. It
provides a framework for users to test properties, where users are
allowed to define customized random generators. However, as far as we
are concerned, existing tools have not taken extensibility of data
generators into consideration. They may have workarounds, though the
extensibility problem is already troublesome in functional languages
like Haskell.

This talk is based on the case study of our work on modular unfolds.
However, the connection to the theoretical part is omitted, and this
work is presented more in a practical view. It is interesting to
understand generators by coalgebras and unfolds, moreover, combinators
are not only designed for extensibility, but they also need to
represent various strategies, making the library more flexible.
