--- 
layout:  post 
title:   Why Withers are not enough. Problems attempting to unify FP and OOP
authors: Marco Servetto
date:    2024-1-15 16:00:00 +0800
venue:   CB308
--- 



We are getting closer and closer to unify functional programming and
object oriented programming.
In particular, it is becoming common to replace mutating a field with
creating a new object that looks like the old one,
but has a different value in that field. Those methods are called
withers, for example ‘withX(int x)’ could create a new Point with the
new value of x, while ‘setX(int x)’ would mutate the current point.
How to fully support the iconic Point/ColorPoint subtyping example
with withers? As we will show, this is not trivial, there are multiple
possible solutions and they are all (in my opinion) unsatisfactory.


> **Zoom link**
> 
> Topic: PL Group Seminar
> Time: Jan 15, 2024 04:00 PM Hong Kong SAR
> 
> Join Zoom Meeting
> https://hku.zoom.us/j/93354032165?pwd=eVN6NFNtbGlaajBKUFdvb2w5RTExUT09
> 
> Meeting ID: 933 5403 2165
> Password: 942828
