---
layout:  post
title:   "Worklist Context"
authors: "Jimmy"
date:    2018-11-13 10:00:00 +0800
venue:   "CB 313"
categories: Jimmy 2018
---
## Abstract
Higher-order polymorphic type systems are powerful and popular these days. We have been trying to find a good algorithm in order to fully formalize the system in a proof assistant. Recently, we propose the "worklist context", which is a context that contains not only variable bindings, but also judgments. In comparison to the previous cascading context, the new approach is easier for people to understand and for proof assistants to encode. Similar to the cascading context, we still get rid of output context by making use of the continuation-passing style.
