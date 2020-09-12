+++
title = "Generating small graphs"
author = ["Joe Corneli"]
lastmod = 2020-09-12T20:51:05+01:00
slug = "generating_small_graphs"
draft = false
+++

Build infra for generating and displaying graphs.

```elisp
(defun triangle (n)
  (if (equal n 0) 0
    (+ n (triangle (- n 1)))))
```


## Related {#related}

-   Possibly link this to [Visual code walk through]({{< relref "visual_code_walk_through" >}}) so that we generate graphs based on code flow.


## Contributes  to {#contributes-to}

-   [Visual Interfaces]({{< relref "visual_interfaces" >}})
