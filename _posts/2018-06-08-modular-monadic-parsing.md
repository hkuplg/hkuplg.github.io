---
layout:  post
title:   "Modular Monadic Parsing with Unfolds"
authors: "Haoyuan"
date:    2018-06-08 10:00:00 +0800
venue:   "CB 313"
categories: Haoyuan 2018
---
## Abstract

Our previous work "type-safe modular parsing", manages to define parsers in a
modular way, which correspondingly generate extensible ASTs. The mechanism
relies on open recursion (in OOP it is reflected by inheritance). The weakness
of the approach is that open recursion scheme is not strong enough to represent
the productivity of parsing. Hence it is worthwhile exploring the relationship
between parsing and coalgebras.

In this talk, I will start with open recursion, and give simple examples on
modular parsers, for a non-modular AST. Then I will generalize the approach to
functors to make ASTs extensible. After that, I will lead a comparison between
Alberto Pardo's approach and this Mendler-style approach. Finally we will
observe how memoization is modularly added to the context.
