---
title: Selective Include
summary: Allow for include to only include specific parts of a page
type: issue
tags: silverbullet,wishlist
date-created: 2023-01-24
link: https://github.com/silverbulletmd/silverbullet/issues/338
---
[[silverbullet|Overview]]

2023-01-24

# Issue
Allow for include to only include specific parts of a page

### description
Make it possible to only include specific parts of an page.

This could be made possible, by markup in the included page:

## Example:
### `included_page.md`
```
# This is includepage

## Description
This is a description of the include


## Usage
Include `included_page.md` for FOO or BAR
It consists of two ranges, you can include:

* FOO :  This is the standard-Text for FOO
* BAR :  This is the standard-Text for BAR

<!-- #include_range section="FOO" -->
FOO foo foo Foo
<!-- /include_range -->

<!-- #include_range section="BAR" -->
BAR bar bar Baz
<!-- /include_range -->

```

### `including_page.md`
```
# Including only BAR
<!-- #include [[included_page]] section BAR-->
BAR bar bar Baz
<!-- /include -->

--------

# Including only FOO
<!-- #include [[included_page]] section FOO-->
FOO foo foo Foo
<!-- /include -->

```


## notice
* The section title is optional
* When the includer specifies a section that is not available in the to-be-included page, then the result is empty
* When the includer does not specify a section, then the result depends on the to-be-included page:
  * If the included page does not define an `include_range` then the result is the whole page (**backward compatibility**)
  * If the included page defines an `include_range` without a section name, then the result is this section
  * If the included page defines one or multiple `include_range`s with section names, then the result will be all the sections with that name in the order they appear in the included page

### state
* [x] open ticket on github
* [x] document link: https://github.com/silverbulletmd/silverbullet/issues/338