---
title: virtual pages
summary: generate "virtual" pages for empty directories
type: issue
tags: silverbullet, wishlist
date-created: 2023-01-24
link: null
---
[[silverbullet|Overview]]  
2023-01-24

# Issue
generate "virtual" pages for empty directories. This can possibly realized with a dedicated PLUG

### description
While creating new pages there are empty directories with no link inbetween.

Imagine the following: whenever a page is requested, that does not exists, but a directory of that name exists, return a page that gets instantanous generated from a selected template file. 
The templatefile to return could be defined with a config setting in the SETTINGS page
As long as the returned page is not edited, it will not be persisted back to disk.

This gives the option to build a template, which contains a link to the parent directory and a simple query to all the pages in that directory, which would allow for simple browsing.


### state
* [ ] open ticket on github
* [ ] document link: 