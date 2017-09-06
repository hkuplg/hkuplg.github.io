--- 
layout:  post 
title:   "let arguments go first, again"
authors: "Ningning"
date:    2017-03-08 10:00:00 +0800
venue:   "CB 313"
categories: Ningning Seminar 2017
--- 
## Abstract

Bi-directional type-checking has proved to be an extremely useful and
versatile
tool for type-checking and type-inference. The conventional presentation of
bi-directional type-checking consists of two modes: inference and checking.
In
checking mode, type annotations are used to guide the
type-inference/checking
procedure to determine the type of an expression. Still, in many cases,
basic
bi-directional type-checking may be heavy on type annotations.

I will presents a variant of bi-directional type-checking that retains
inference
mode, but adds a so-called application mode. The application mode can also
be
used in combination with checking mode, but in many systems inference and
application modes are sufficient. Bi-directional type-checking with
application
mode leads to a different design for the application rule, where the types
of
the arguments are inferred first, and then used to guide the inference of
the
function being applied. Such design can remove annotations that basic
bi-directional type-checking cannot. To illustrate the utility of the
application mode, I will present a new way to do type-inference for
higher-ranked types. The new design is interesting for two reasons. Firstly
it
provides a generalization of the Hindley-Milner (HM) type system without
resorting to a built-in let construct. Types for programs that are inferred
in
HM are also inferred in this system, but in this system let is modeled via
the
standard application/lambda sugar. Secondly, unlike most existing
algorithms,
this system can, in some cases, infer higher-ranked types without type
annotations.


