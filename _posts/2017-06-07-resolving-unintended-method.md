--- 
layout:  post 
title:   "Resolving Unintended Method Conflicts"
authors: "Yanlin"
date:    2017-06-07 10:00:00 +0800
venue:   "CB 313"
categories: Yanlin Seminar 2017
--- 
## Abstract

We propose a new multiple inheritance model for unintended method conflicts.
Existing approaches including static dispatch and dynamic dispatch have to
compromise between code reuse and type safety, whereas our model uses a
different solution called hierarchical dispatch to obtain both. Such an
approach
not only offers great code reuse like dynamic dispatch, but also ensures
unambiguity by our algorithm for method binding. This model also introduces
partial overrides on methods. It is formalized with a basis on Featherweight
Java.


