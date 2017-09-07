--- 
layout:  post 
title:   "How to Make FCore Thread-safe"
authors: "Jeremy"
date:    2015-03-05 13:45:00 +0800
venue:   "CB 313"
categories: Jeremy 2015
--- 
## Abstract

Last week, we submitted a revised paper about the representation of
functions and optimization used in our compiler back-end. One reason
that compels us to revise our previous work is the concern of
thread-safety in FCore.

In the first half of the seminar talk, we will first see what will go
wrong when the generated Java code is used in a multi-threading
setting without special treatment. Then I will propose a
obvious-yet-incorrect solution to workaround it. Finally, I will
present a promising solution that works well with System F binders.

In the second half, I will briefly talk about a useful technique of
working with PHOAS that is used in our compiler to make simplifier
work correctly with the back-end. We will see three rewriting rules
and how these rules are implemented using the technique.

Finally I will discuss the some future work and related work done by
others.

