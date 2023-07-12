---
layout:  post
title:   "Backwards Bidirectional Typing for Non-Linear Terms, Leveraging Intersection Types"
authors: Snow
date:    2023-07-13 10:10:00 +0800
venue:   CB308
---

In this problem session, I will talk about backwards bidirectional typing, where
information flow is unconventional. It is designed for linear logic, in which
every assumption is used exactly once. With the help of intersection types,
such design can be applied to non-linear terms, and enable type systems like
lambdai to accept more terms with less annotation.
