## 
[Hints and principles for computer system design](https://www.microsoft.com/en-us/research/uploads/prod/2019/09/Hints-137-short.pdf)

##
[Domain-Driven](https://www.dddheuristics.com/)

[DDD and Messaging Architectures](https://verraes.net/2019/05/ddd-msg-arch/)

[API Design](https://github.com/keras-team/governance/blob/master/keras_api_design_guidelines.md)

---

## Distributed Systems

[Kubernetes](Kubernetes.md)

## Design Patterns
The concept of design patterns dates back to the 1970s and from the field of architecture. Christopher Alexander, an architect and system theorist, and his team published the groundbreaking [A Pattern Language](https://en.wikipedia.org/wiki/A_Pattern_Language) (Oxford University Press) in 1977, which describes architectural patterns for creating towns, buildings, and other construction projects. Sometime later this idea was adopted by the newly formed software industry. The most famous book in this area is [Design Patterns—Elements of Reusable Object-Oriented Software](https://en.wikipedia.org/wiki/Design_Patterns) by Erich Gamma, Richard Helm, Ralph Johnson, and John Vlissides—the Gang of Four (Addison-Wesley). When we talk about the famous Singleton, Factories, or Delegation patterns, it’s because of this defining work. Many other great pattern books have been written since then for various fields with different levels of granularity, like [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com/) by Gregor Hohpe and Bobby Woolf (Addison-Wesley) or [Patterns of Enterprise Application Architecture](https://www.martinfowler.com/books/eaa.html) by Martin Fowler (Addison-Wesley).

In short, a pattern describes a repeatable solution to a problem.[1] It is different from a recipe because instead of giving step-by-step instructions to solving a problem, a pattern provides a blueprint for solving a whole class of similar problems. For example, the Alexandrian pattern “Beer Hall” describes how public drinking halls should be constructed where “strangers and friends are drinking companions” and not “anchors of the lonely.” All halls built after this pattern look different, but share common characteristics such as open alcoves for groups of four to eight and a place where a hundred people can meet with beverages, music, and other activities.

However, a pattern does more than provide a solution. It is also about forming a language. The unique pattern names form a dense, noun-centric language in which each pattern carries a unique name. When this language is established, these names automatically evoke similar mental representations when people speak about these patterns. For example, when we talk about a table, anyone speaking English assumes we are talking about a piece of wood with four legs and a top on which you can put things. The same thing happens in software engineering when we talk about a “factory.” In an object-oriented programming language context, we immediately associate with a “factory” an object that produces other objects. Because we immediately know the solution behind the pattern, we can move on to tackle yet unsolved problems.

There are also other characteristics of a pattern language. Patterns are interconnected and can overlap so that together, they cover most of the problem space. Also, as already laid out in the original A Pattern Language, patterns do not have the same level of granularity and scope. More general patterns cover an extensive problem space and provide rough guidance on how to solve the problem. Granular patterns have a very concrete solution proposal but are not as widely applicable. This book contains all sort of patterns, and many patterns reference other patterns or may even include other patterns as part of the solution.

Another feature of patterns is that they follow a rigid format. However, each author defines a different format, and unfortunately there is no common standard for the way patterns should be laid out. Martin Fowler gives an excellent overview of the formats used for pattern languages in [Writing Software Patterns](https://www.martinfowler.com/articles/writingPatterns.html).

1. Christopher Alexander and his team defined the original meaning in the context of architecture as follows: “Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice,” (A Pattern Language, Christopher Alexander et al., 1977, p. x).