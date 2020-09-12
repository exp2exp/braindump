+++
title = "DATA COURSE"
author = ["Joe Corneli"]
lastmod = 2020-09-12T21:07:36+01:00
slug = "data_course"
draft = false
+++

There's a new book from the group affiliated with STAN.  It doesn't go
very far but it has tons of examples.  They have data sets about all
sorts of stuff.  So the idea would be to take, e.g., the notebook on
linear regression, and go through...


## Idea {#idea}

Start with a method, then go through lots of examples.  Make this
consistent with the way we would teach HtDP.

"Here's a data set, here's a method that would make sense to apply."


## Sources {#sources}

There are tons of great data sets, but the issue would be digging into
the details of some of them.  The real issue is coordinating.  We want
to start with e.g., intro to linear regression, then hierarchical
linear regression, and working up to things like Lotka-Voltera model.

-   Datopian


## How to build up to this? {#how-to-build-up-to-this}

-   E.g., setting up the pre-requisites of the platform
-   Setting up a tutorial on model building in a certain domain, get 10 people in the specialised tutorial, how is it received
-   This would start building up the group of people
    -   Using someone else's platform would be different from using our own platform
    -   Which of these is the focus? (**Good question but let's have one or two sprints beforehand to see where things are going.**)


## Assumptions {#assumptions}

-   Keep platform open source, assume people would want to use


## Comments {#comments}

-   Platform is quite a general word, but in a way we are trying to make something easier
-   The platform is just an interface to a piece of technology we build.  The core is really on the backend.
-   So the focus should be on the backend not on the javascript bits.
-   Maybe leverage more existing technologies for the platform, where building it basically means installing it.
-   Nextjournal: this looks good because they have UX designers to polish things
-   Cloud-based Emacs: Would allow you to back your instantiation as if Emacs is your operating system, 500GB instance on Google Cloud


## Status {#status}

-   Cameron has code to set up a multicluster platform available off the shelf that we can start with
-   Ray has been doing similar things for personal use, though if this helps write biology papers.
-   What if our user interface was Emacs?
    -   Different keybindings; developers like Emacs or Vi...
    -   Org Bable exists & we can refer to this for now


## Reference {#reference}

-   Michael Betancourt: Towards a principled bayesian workflow


## Next steps {#next-steps}

-   [Bottom]({{< relref "bottom" >}})


## Backlinks {#backlinks}

-   [Code sharing platform]({{< relref "code_sharing_platform" >}})
