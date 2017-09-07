--- 
layout:  post 
title:   "Functional extensible parsers"
authors: "Haoyuan"
date:    2016-08-11 15:00:00 +0800
venue:   "CB 313"
categories: Haoyuan 2016
--- 
## Abstract

Parsing is a non-trivial problem in designing compilers, and especially code
reuse in parsing is important and helpful. There have been several
"extensible"
parsers in the past, including xoc, polyglot, noa, etc. But none of them
leads
to real extensibility, generally the extensible grammars they support merely
copy & paste the code by users, and generate a new parser as a whole
whenever
the grammar rules are modified or extended. Basically we would like to have
an
extensible parser, supported by a strong (functional) type system, so that
type-safety and separate compilation are ensured. We have done some initial
work
in Haskell. Datatypes in Haskell are not directly extensible, nevertheless,
approaches in DTC and MRM inspired us a lot. Our prototype is based on the
machenism in MRM, and meanwhile open recursion is introduced, leading us to
a
real extensible and recursive parser. In the presentation, we will have a
closer
look at the framework together with some examples, and end with discussion &
future work.


