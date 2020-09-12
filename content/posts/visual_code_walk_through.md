+++
title = "Visual code walk through"
author = ["Joe Corneli"]
lastmod = 2020-09-12T21:07:52+01:00
slug = "visual_code_walk_through"
draft = false
+++

Ray is working on a visual code walk through.


## General evaluation strategy for these demos: {#general-evaluation-strategy-for-these-demos}

-   _‘Would anyone want to use this?’_
-   E.g., in the case of Emacs "learn X in Y" demo.
-   If there is interest, work up to covering the HtDP book


## Related work {#related-work}

MAUDE framework.
: You describe your programming language using
    rewrite rules in K.  They define tools to auto-derive rules in [K](http://www.kframework.org/index.php/Projects).


Program slicing
: ‘Galois connection on the traces’. This allows
    you to find where bugs appeared.  People tend to look in the most
    recent.  Imagine a call-graph of all the variables, so it gives you
    a minimum trace, showing where your bug can be found.


## Next steps {#next-steps}

-   [Teach basic coding]({{< relref "teach_basic_coding" >}})


## Backlinks {#backlinks}

-   [Generating small graphs]({{< relref "generating_small_graphs" >}})
