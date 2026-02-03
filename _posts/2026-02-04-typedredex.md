--- 
layout:  post 
title:   A typed embedding of Redex DSL in Haskell
authors: Xu Xue
date:    2026-02-04 09:30:00 +0800
venue:   CB308
--- 

Join tomorrow's problem session for a look at TypedRedex, my recent side project where I've rebuilt [PLT Redex](https://github.com/racket/redex) from the ground up in Haskell. 
The biggest shift? We’ve moved away from Racket’s dynamic nature to a system where (almost) everything is statically checked. 
It’s Redex, but with the internal logic solver entirely reconstructed for various purposes. 
You can write your code similiar to rules presented the paper, and you can then execute, inspect, property-test and even typeset it without any efforts.

Check it out and happy discussing!
