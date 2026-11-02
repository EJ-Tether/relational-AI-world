---
title: "Review copies"
# Pages placed in this folder are built and reachable by their URL only:
# they appear in no list, RSS feed, tag page, sitemap or search index,
# and carry a "review copy" banner. To publish, move the file to content/posts/.
# To withdraw, delete it: the link then returns a 404.
build:
  render: never
  list: never
cascade:
  build:
    render: always
    list: never
  robots: "noindex, nofollow"
  reviewCopy: true
---
