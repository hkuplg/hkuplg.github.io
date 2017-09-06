--- 
layout:  post 
title:   "Encoding GADTs with Type Equality Constraints"
authors:  "Yanlin"
date:     2016-01-14 14:00:00
venue:   "CB 328"
categories: "Yanlin" Seminar 2016
--- 
## Abstract

Encoding GADTs in the originally proposed core language λμ* is not
easy, because of lacking type equalities. Though it is possible to use
the existing language constructs, like one-step casts, to encode GADTs
using Leibniz equality, some critical problems, such as injectivity of
datatype constructors still remain. We propose new language extensions
to λμ*, called type equality constraints, to introduce explicit type
equality evidence into the system for extra expressiveness. In this
talk, we show how new language constructs can avoid bogus proof issues
in other systems with equality types. We also show the adapted Scott
encoding for GADTs by using constraints and how this approach solved
the problems discussed in our last talk.
