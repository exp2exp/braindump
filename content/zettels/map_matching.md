+++
title = "Map Matching"
author = ["Jethro Kuan"]
lastmod = 2019-12-03T23:02:51+08:00
draft = false
math = true
+++

Map matching compiles small numbers of consecutive scans into
local maps \\(m\_{\mathrm{local}}\\). Maps are then compared to the global
map \\(m\\), such that the more similar \\(m\\) and \\(m\_{\mathrm{local}}\\), the
larger \\(p(m\_\mathrm{local} | x\_t, m)\\). Cells in the local map are
transformed to the coordinates of the global map, and the map
correlation function is computed.

Map matching is easy to compute, but does not yield smooth
probabilities in the pose parameter \\(x\_t\\). One solution is to convolve
the map with a Gaussian smoothness kernel before running map matching.

Map matching considers the free-space in the scoring of 2 maps,
compared to the [§likelihood\_field\_model]({{< relref "likelihood_field_model" >}}) which uses only the
end-points.


## Issues {#issues}

1.  No plausible physical explanation
2.  Result of map matching may incorporate areas beyond actual
    measurement range.


## Related {#related}

-   [§likelihood\_field\_model]({{< relref "likelihood_field_model" >}})