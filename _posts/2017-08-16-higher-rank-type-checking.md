--- 
layout:  post 
title:   "Higher-Rank Type Checking with Worklist"
authors: "Jimmy"
date:    2017-08-16 10:00:00 +0800
venue:   "CB 313"
categories: Jimmy 2017
--- 
## Abstract

Higher-rank type checking is powerful and convenient for programmers, but
such
systems are often complicated. Dunfield proposed a "complete and easy"
bidirectional type system together with an algorithm. However, lots of
tricks
used in his proof are hard to mechanize and to be checked by proof
assistants.
In this talk, we will show another algorithmic system which makes use of
worklists and discards output contexts. Important theorems on subtyping
relations are proven in Abella, while Dunfield's bidirectional typing
system has
not been fully adapted yet.


