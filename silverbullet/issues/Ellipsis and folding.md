---
title: Ellipsis and folding
summary: Directive to allow folding/ellipsis of a section
type: issue
tags: silverbullet, wishlist, directive
date-created: 2023-01-24
link: https://github.com/silverbulletmd/silverbullet/issues/342
---
[[silverbullet|Overview]]  {[Page: Delete]}

2023-01-24

# Issue
Directive to allow folding/ellipsis of a section

### description
As a user I want a directive that I can wrap around a section of text, that when rendered, allows me to fold/unfold the contents or shorten the displayed content to an specified amount, followed by ellipsis.

---
`example.md`
```
<!-- #fold -->
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi ac magna urna. Vestibulum ex lacus, aliquet ac mi at, faucibus venenatis elit. Phasellus mattis non orci eu lacinia. Integer libero sapien, tempus sit amet consectetur vulputate, laoreet vel justo. Proin gravida maximus feugiat. Maecenas magna quam, porta ac pellentesque at, tempus nec velit. Donec ut lobortis ante, eu ullamcorper nisl. Integer placerat a quam et pretium. Mauris elit orci, sagittis et augue ullamcorper, sollicitudin sodales turpis. Morbi auctor, nisi ultricies fermentum venenatis, libero risus dictum risus, ut sagittis mi ante sit amet risus. Aliquam sed nunc vehicula, imperdiet risus quis, ultricies erat. Nullam in turpis nec turpis aliquam faucibus. Praesent viverra placerat elementum. Maecenas ac tempus massa. Nulla elit sem, eleifend id metus fringilla, interdum feugiat nulla. Donec vestibulum lectus sed lacus interdum sagittis.

Pellentesque eleifend consequat sem, sed dignissim ipsum lobortis vitae. Pellentesque cursus risus vitae volutpat placerat. Suspendisse potenti. Ut consectetur turpis eget justo efficitur convallis. Nullam ullamcorper nibh eget consequat suscipit. Maecenas at faucibus purus. Donec vitae volutpat neque. Vestibulum sit amet libero ornare, pharetra felis non, bibendum velit. Donec cursus est et magna porttitor, sed sagittis felis eleifend. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.

Donec viverra metus vitae tellus luctus semper. Donec tincidunt nulla eu enim aliquam sagittis. Nulla ornare sollicitudin metus id consectetur. Sed aliquet massa a nunc vehicula, in tempor nibh auctor. Cras vestibulum et ligula eu pharetra. Nulla scelerisque nulla eget porttitor ultricies. Aenean tempor in massa vel vulputate. Nullam scelerisque, orci a congue placerat, urna sapien ultricies nisl, ut volutpat lacus leo vel justo. Etiam pulvinar egestas erat, vel mollis eros efficitur at. In bibendum risus purus, ac vestibulum leo mattis sit amet. Ut rhoncus pharetra ex faucibus condimentum. Aenean ultrices ex in nunc faucibus pellentesque. Pellentesque lacus purus, luctus ut velit ac, sagittis pulvinar ipsum. Nulla sodales urna non imperdiet lobortis. Donec consectetur elit tincidunt purus dictum tempus a vel turpis.

Maecenas eleifend eleifend lorem et pharetra. Etiam facilisis felis metus, eget imperdiet nibh porttitor vitae. Proin a sollicitudin metus. Vivamus porta porttitor metus nec vehicula. In malesuada malesuada dui, eleifend blandit nisl auctor eu. Ut hendrerit ac metus in placerat. Cras consequat velit sit amet sem varius, quis consequat risus venenatis. Suspendisse mattis sapien ornare ante vulputate sodales. Pellentesque ornare justo non diam aliquet vestibulum at non felis. Sed condimentum pulvinar lorem id mollis. Mauris malesuada vulputate ligula, vitae auctor quam consequat sit amet. Donec porta dui in pretium iaculis. Vestibulum sollicitudin sem ac lacus euismod, ut ornare neque consectetur. Vestibulum nec pharetra turpis. Phasellus tristique mi lectus, et cursus urna congue at. Nulla eu interdum quam.
<!-- /fold -->
```
---
will render as 

---
```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi ac magna urna. Vestibulum ex lacus,
```
[[...]]

---
### state
* [x] open ticket on github
* [x] document link: https://github.com/silverbulletmd/silverbullet/issues/342