---
layout:  post
Title: "DuoTyping: Examining the generalized subtyping"
Speaker: Baber
Date: 2019-07-23 10:00:00
Venue: CB313
---
## Abstract
Subtyping is a concept frequently encountered in many programming
languages. Many languages with parametric polymorphism allow users to
impose upper bounds to the type variables. This feature is captured in
System F<: , which has been studied quite thoroughly in the literature.
Languages like Scala also allow programmers to constrain type variables to
be supertypes of certain types. In this project, we examine the effect of
combining the relations of subtyping and supertyping into a single judgment
with a mode of relationship.This allows us to study calculi with both upper
bounds and lower bounds imposed on type variables, and to simplify the
subtyping transitivity proof in some cases. For the project, we examined
several type systems with a generalized subtyping judgment that expresses
both subtyping and supertyping relations. Doing so allows us to examine
properties of specific type systems where a lower bound can be imposed on a
type variable,and sometimes allow us to simplify the subtyping transitivity
proof by utilizing the duality of subtyping and supertyping.
