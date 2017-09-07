--- 
layout:  post 
title:   "Symbolic Property-based Testing for Functional Languages"
authors: "Weixin"
date:    2015-09-24 14:30:00 +0800
venue:   "CB 313"
categories: Weixin 2015
--- 
## Abstract

QuickCheck is the de facto testing tool for functional languages,
which is a combination of the three testing methodologies -
property-based testing, black-box testing and random testing. Users of
QuickCheck often need to define generators which is tedious and
error-prone. Also, the nature of black-boxing makes it hard for
QuickCheck to find bugs in some cases.

In this talk, I will first motivate our work by summarising the
limitations of QuickCheck. And then I will introduce how symbolic
execution can be applied to property-based testing through
examples. Lastly, I will summarise the pros and cons of our approach
and show some case studies we have performed.

