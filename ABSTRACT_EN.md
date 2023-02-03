# Talk Abstract

Data representation is a critical skill, and yet one that is often overlooked in training material. Instead, we tend to rely on ready-made conclusions without questioning them.

In this talk, we’ll model a simple programming language to explore the design space, and do some serious questioning.


# Talk Description


Modelling data types is a critical aspect of programming: coming up with the right data representation can mean the difference between clear, efficient code, and an unholy mess of spaghetti code with tons of forgotten edge cases.

At the same time, there’s a fundamental tension between what’s commonly known as “the OOP approach” and “the FP approach”, where the former introduces a tight coupling between data and behaviors, and the latter does the exact opposite.

In this talk, we explore both by attempting to represent and interpret a (very simple) programming language using “the OOP approach”, observing the pain points, and seeing what different set of properties we get by fixing them. By the time we’re done, we’ll have explored a large chunk of the design space, and learned lessons on the various tradeoffs one makes by choosing one approach over the other.

Importantly, we try to stay away from oversimplifications such as FP good, OO bad. We hope to demonstrate that both approaches are interesting and valid, and choosing one should be a matter of context rather than religious belief.

# Notes

I initially wanted to do this talk because of the amount of developers, junior or otherwise, I’ve worked with that had no training in data representation. Most of them had not heard of sum types (or however the host language calls them), let alone of the benefits they bring. Showing them has led to a noticeable increase in the quality of their code, once the “let’s use that new tool for everything” phase was over.

Another justification is that, in my programming circles, there’s a certain hostility between FP and OOP programmers, and quite a bit of condescension from the FP side. I’ve found this to put perfectly good developers off of FP altogether, because obviously, when an entire community makes fun of skills you’ve taken years to master and looks down on you for having done so, you might not be keen to join it. I quite like to puncture that bubble of self-satisfaction, and have found that presenting FP as a reasonable alternative to OOP, depending on the context, tended to be a far more efficient way of teaching than the usual _your way is bad and you should feel bad_ spiel.

This talk is a thinly veiled introduction to the Expression Problem. The opposition of Abstract Data Types (easy to add types, hard to add behaviours) and Algebraic Data Types (easy to add behaviours, hard to add types) is, or rather, should be well known. The purpose of this talk is to try and introduce more relative beginners to this idea, and try to dispel simplistic ideas such as “OOP is morally wrong and should never be used” before they have a chance to take root.

This ideological argument, while important, is also an excuse to actually show how to represent data in a useful fashion, and how separating data from interpretation can be quite a good idea.
