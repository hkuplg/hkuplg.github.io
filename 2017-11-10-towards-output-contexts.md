---
layout:  post
title:   "Towards machanized proofs on output contexts"
authors: "Jimmy"
date:    2017-11-10 10:00:00 +0800
venue:   "CB 313"
categories: Jimmy 2017
---
## Abstract

Output contexts play an important role in some type systems. They are used to
record the state of type inference and transfer information across the program.
Due to technical reason, they are hard to formalize in proof assistants.
Recently, we proposed a way, i.e. the worklist approach, to formalize
higher-order subtyping relations without output contexts, and successfully
proved the meta-theory in Abella. However, we failed to find a type system where
worklist benefits. Therefore, we try to adopt output contexts and formalize
them. Interestingly, Abella is able to handle some difficulties about such
systems. In this talk, I will briefly compare Locally Nameless (a Coq library)
with Abella, and talk about the advantages of Abella when dealing with output
contexts.

A little understanding on Dunfield's type system
(http://www.cs.cmu.edu/~joshuad/papers/bidir/), Coq, and the Locally Nameless
library is expected, though not required. No backgrounds about Abella is
expected.
