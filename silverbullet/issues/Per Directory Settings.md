---
title: Per Directory Settings
summary: some settings should be possible to overwrite on a directory basis
type: issue
tags: silverbullet, wishlist, settings
date-created: 2023-01-24
link: null
---
[[silverbullet|Overview]]  {[Page: Delete]}

2023-01-24

# Issue
some settings should be possible to overwrite on a directory basis

### description
In Ticket ... I suggest configurable Header, Footer and Sidepages. The template to use should be configured via `SETTINGS`. 

Also the setting, which templates to use for pages or snippets can be set in such a way, that directories and entire subtrees can stay self-contained by providing their own templates.

This allows for easier namespacing concerning filenames ...

These and also other settings(where sensible), should be able to be overwritten by a `SETTINGS` file per directory.

This means, that if a page is shown that is stored in a directory, lets say `/foo/bar/quux/BlaFasel.md` then the following settings should be read in the order, with the latest one overwriting the former:

* `/SETTINGS`
* `/foo/SETTINGS`
* `/foo/bar/SETTINGS`
* `/foo/bar/quux/SETTINGS` 

### state
* [ ] open ticket on github
* [ ] document link: 