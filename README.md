# site-web
Site web perso
---
layout: page
title: Overview of GitHub Pages
description: Overview of construction of a website with GitHub Pages
---

The present site is simple, with a style derived from
[JekyllBootstrap](https://jekyllbootstrap.com/) and
[Twitter Bootstrap](https://getbootstrap.com) with a particular
theme. I'll explain how to create a site with exactly this style. If
you want something else, try the
[GitHub Pages](https://pages.github.com) automatic site generator, or
look at the [resources page](pages/resources.html).

These GitHub Pages sites are constructed by having a `gh-pages` branch
of a GitHub repository, with specific files layed out in a specific
way. To see the structure of such a repository, look at the
[repository for the present site](https://github.com/kbroman/simple_site).



The directories beginning with an underscore contain materials
defining the basic layout and style for the site. If you
[build the site locally](pages/local_test.html) (for testing
purposes), there will also be a `_site/` directory containing the
actual site (with
[Markdown](https://daringfireball.net/projects/markdown/) files
converted to html). You don't want the `_site/` directory in your
repository, so include that in the `.gitignore` file.
