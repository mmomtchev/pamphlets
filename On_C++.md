# C and C++

Recently there has been another around of public debates on the future of C++ - one that even prompted a statement from its author, Bjarne Stroustrup.

As most of my time during the last 5 years has been spent implementing interfaces between C++ and the new most popular kids in the block - JavaScript and TypeScript - I thought that I had my 2 cents to share.

The original C is without any doubt the most influential language in the history of IT. An incredibly versatile language, created in order to write the UNIX kernel, it has been used - and abused - far beyond any other language. Combining ultra-high performance with good abstraction, it was the ultimate language for system software. Despite its infamous pitfalls, it was so good, that people abused it for many tasks it was never supposed to be good at - there was a time during the 1980s when people used to combine C with PL/SQL to write business software. A horrible abomination born out of practicality - since every system had a C compiler and every programmer knew C. Using C meant that you were interoperable with everything and everyone.

C++ built upon that legacy a truly universal higher level language - one that was supposed to be able to compete with both the very fashionable 5th generation languages of the era, and the lower-level ultra-high performance C. All this came at a cost - an incredibly complex language that took C pitfalls to a whole new level.

C++ remains the most versatile language ever. It sits in its own category. No other language comes anywhere close.

It is also the most interoperable language - there are very few cases where the interaction between two other languages does not include a C or a C++ layer.

The current debate seems to be mostly centered on its manual memory management - its most remarkable feature - when compared to its other high-level competitors in 2025.

**The manual memory management in C++ is not its biggest drawback - the manual memory management is its most important feature.**

Even in 2025, it remains the prime choice for operating systems, database engines, dynamic language interpreters and 3D game engines. Even in 2025, C++ software tends to be leaner, more portable to different platforms, and faster than everything else.

It also tends to be far more expensive to develop.

This means that using C++ for anything else besides core software is most certainly a waste of resources.

Expressing business logic or complex mathematical models - especially those that require parallel computation - in C++ is simply wasteful. In a web application, nothing besides the network protocol suite should use it. In a complex high-performance computing model, nothing besides the distribution and synchronization primitives and the low-level SIMD matrix operations should use it. Because for this kind of software, zero memory copy transfers still matter and there is an actual benefit from it.

For everything else, the algorithm is where the main effort should be focused.
