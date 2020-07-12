---
layout:  post
Title: Type Inference via Worklist Context
Speaker: Jimmy
Date & Time: 2019-04-30 10:00:00
Venue: CB313
---
## Abstract
We have studied new higher order type inference algorithms via the worklist form for a long time. Recently the first full algorithmic type system is developed on top of Dunfield and Krishnaswami's declarative system.
Worklist algorithm benefits from its visibility to a collection of judgments, thus solving and substiting meta variables are much easier compared with traditional algorithms. Important properties, including soundness, completeness and decidability, are proven in the Abella proof assistant.
In this talk I am going to talk about the algorithm again, and discuss one major issue we just overcome on the overlapping rules---so that the algorithm is deterministic and directly implementable.