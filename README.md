# Notes

[![Netlify Status](https://api.netlify.com/api/v1/badges/0111b10b-7d79-4e36-bc92-38c7075da244/deploy-status)](https://app.netlify.com/sites/exploretoexploit-notes/deploys)

This is a repository for [org-roam](https://www.orgroam.com/) notes. It is a fork of [jethrokuan/braindump](https://github.com/jethrokuan/braindump/).

## Jethro's Braindump

This braindump is generated via [ox-hugo][ox-hugo] and uses the
[cortex][cortex] theme.

The org files used to generate the markdown files are also hosted here
for posterity. They can be found in [the org folder][org].

## Regenerating files



## Installation instructions

Install [hugo][hugo]. E.g., on a Mac with Homebrew:

    $ brew install hugo

Make sure the submodule containing the Hugo theme is installed:

    $ git submodule init
    $ git submodule update

Now run hugo to generate the files (find them in `/public`):

    $ hugo

Or run the following to get an immediately browsable website on localhost:

    $ hugo serve

[hugo]: https://gohugo.io/
[ox-hugo]: https://github.com/kaushalmodi/ox-hugo
[cortex]: https://github.com/jethrokuan/cortex
[org]: https://github.com/jethrokuan/braindump/tree/master/org
