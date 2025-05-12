--- 
layout:  post 
title:   Free Variables as Bitmaps
authors: Xu Xue
date:    2025-05-14 10:10:00 +0800
venue:   CB308
--- 

During proofs involving well-scoped de Bruijn infrastructure (WSDB), 
I’ve often preferred avoiding free variable sets for defining judgments 
(well-formedness, closeness, occurrence checking and etc.), 
relying instead on structural induction over terms/types. 
While this usually works, 
structural induction sometimes fails to deliver satisfactory induction principles, 
here free variable representations can help.

The idea of representing free variables representation as bitmaps, 
appeared as a small trick, but commented by Bruno "ah, never seen this before". 
That's why I decided to dig more as a problem session.

Interestingly, it turned out to offer more than just making some lemmas provable,
but many other lemmas came for free, simplifying the proof, and it works good with WSDB.
