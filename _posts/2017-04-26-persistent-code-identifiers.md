--- 
layout:  post 
title:   "Persistent Code Identifiers for Dependency Management"
authors: "Tomas"
date:    2017-04-26 10:00:00 +0800
venue:   "CB 313"
categories: Tomas 2017
--- 
## Abstract

Code organization and distribution have mimicked name-addressable file
system
semantics: we name our code and group it in hierarchies of namespaces. We
bundle
such organized code in libraries and distribute it through global package
repositories. Depending on a repository policy, code in our library may have
name collisions with code in other libraries or previous versions of our
library. Beyond that, client code that depends on our library may only
require a
portion of its API. Library-level dependency tracking, however, enforces
unused
code to be always included. We then need to process all of unused code and
worry
about its changes and conflicts. We can prevent these problems by using two
techniques: assigning unique identifiers to code definitions based on their
content and maintaining code dependencies on a definition level. Several
experimental programming languages use this approach in their design. In
this
talk, we examine how we can apply this approach in an existing programming
language, ClojureScript. We identified challenging language features and
analyzed existing source code repositories for effects of using this
approach.


