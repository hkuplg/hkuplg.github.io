--- 
layout:  post 
title:   "Encoding GADTs with Casts"
authors: "Linus"
date:    2015-10-15 14:30:00 +0800
venue:   "CB 313"
categories: Linus Seminar 2015
--- 
## Abstract

We previously introduced a tiny core language (λμ*) with explicit
casts. Its surface language "Fun" supports algebraic data type and
pattern matching by Scott Encoding, but lacks support for GADTs
(Generalized Algebraic Data Types). In fact, certain forms of GADTs
can already be encoded into the vanilla core. But due to the lack of
explicit equality and injectivity, some functions on GADTs are
impossible to express. In this talk, we show how to encode GADTs and
pattern matching on GADTs with explicit casts. We also address the
limitation of the current core by giving some examples that fail to be
translated. Finally, we propose some feasible solutions to these
issues.

