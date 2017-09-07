--- 
layout:  post 
title:   "Towards First-class Modules in Dependently Typed Languages"
authors:  "Jeremy"
date:     2015-12-17 14:00:00 +0800
venue:   "CB 313"
categories: Jeremy 2015
--- 
## Abstract


Modules matter most. When it comes to controlling the complexity for
large-scale software development, modularity is the most effective
weapon. Although most modern programming languages support modular
programming and code reuse in one form or another, of particular
interest is the module system in the languages of the ML family.

In the first half, we will have a crash course on the ML-style module
systems. We will see key features shared by all the dialects of the ML
modules system, namely namespace management, fine-grained variety of
interfaces, client-side data abstraction (via functors),
implementation-side data abstraction (via sealing) and so on.

In the second half, we will talk about some design issues of the
ML-style module systems: why it is so complex, why first-class modules
are difficult. Then I will present some preliminary results of combing
ML-style module systems with our dependently typed language. The
outcome is appealing, in the sense that we will have a much more
powerful module system (aka first class modules) with less syntactic
constructs.



