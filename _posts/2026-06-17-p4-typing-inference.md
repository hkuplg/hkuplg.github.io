--- 
layout:  post 
title:   Type Inference for P4 language
authors: Jingqi Xiao
date:    2026-06-17 09:30:00 +0800
venue:   CB308
--- 

I'll introduce a type-inference system for a P4-like data-plane language, with a focus on inferring compact and resource-aware bit widths. The implementation supports local inference, function calls, width constraints, and practical language features such as records, controls, and tables. On the formal side, the project studies a smaller core calculus that captures the main technical ideas: expression-sized bit types, declarative and algorithmic typing, subtyping, and metatheory.