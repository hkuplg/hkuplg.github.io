--- 
layout:  post 
title:   "Modular Architecture for Code and Metadata Sharing"
authors: "Tomas"
date:    2016-03-11 16:00:00 +0800
venue:   "CB 313"
categories: Tomas 2016
--- 
## Abstract

Every fragment of code we write has dependencies and associated metadata.
Code
dependencies range from local references and standard library definitions to
external third party libraries. Metadata spans from within source code files
(hierarchical names and code comments) to external files and database
servers
(package-level dependency configurations, build and test results, code
reviews
etc.). This scattered storage and non-uniform access limits our programming
environments in their functionality and extensibility. In this paper, we
propose
a modular system architecture, Haknam, better suited for code and related
metadata sharing. Haknam precisely tracks code interdependencies, allows
flexible naming and querying of code references, and collects code
fragments and
their related metadata as messages in a distributed log-centric pipeline. We
argue that this setting brings considerable advantages. In particular, we
focus
on modular development of tools and services that can assist in
programming-related tasks. Every new functionality can be simply added by
creating and processing messages from the distributed pipeline.


