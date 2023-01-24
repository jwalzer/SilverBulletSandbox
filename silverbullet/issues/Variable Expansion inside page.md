---
title: Variable Expansion inside page
summary: Allow expansion of variables inside the page via handlebars
type: issue, wishlist
tags: silverbullet
date-created: 2023-01-24
link: https://github.com/silverbulletmd/silverbullet/issues/336
---
[[silverbullet|Overview]]

2023-01-24

# Issue

Allow expansion of variables inside the page via handlebars

### description

As a user I want to generate Text on a page, that is filled from variables. Variables can be set from frontmatter.
This allows for generating some kind of standard-texts or in my case system documentation with help of the templating engine.

I’d like be able (in a first step) to just refer to elements from frontmatter via handlebar syntax.

Additional tokens that would be valuable to have access to:
* `currentPage`
* `parentPage`
* `TOC` - TableOfContents
* `siteURL` - which is an attribute which should be configured in the `SETTINGS` page
* 

### state
* [x] open ticket on github
* [x] document link: https://github.com/silverbulletmd/silverbullet/issues/336