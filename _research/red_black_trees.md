---
title: Left-Leaning Red-Black Trees
excerpt: "A 2014 undergraduate research project. We investigated an alternative,
lighter-weight implementation of Red-Black trees."
date: 2014-03-05
---

This work was a 2014 undergraduate research project sponsored by Professor Duane Bailey and presented during Williams [computer science colloquium](https://csci.williams.edu/student-thesis-talks-part-ii/) spring 2014.
## Abstract
Red-Black trees are often considered to be a data structure too complex to implement or teach effectively. We aim to show that a few slight modifications to the Red-Black tree can provide a simpler and lighter weight implementation, called the Left-Leaning Red Black Tree. Within its operations it prefers to hang nodes to the left when possible, which allows procedures like _add_, _remove_, and _contains_ to be implemented with relatively simple recursive calls. Testing our implementation of a Left-Leaning Red Black Tree against other similar data structures has shown us that it is competitive in both run-time and length of code.

### [Presentation]({{site.baseurl}}/pdfs/llrb_presentation.pdf) | [Repository](https://github.com/tliu526/llrb-trees)
