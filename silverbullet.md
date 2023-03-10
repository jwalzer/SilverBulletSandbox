# Project Silverbullet


{[Template: Instantiate Page]}

___
The following Text will be posted in the SB Discussion board:
<!-- #include [[silverbullet/GeneralText]] -->
## Why and What

The moment I saw the demo video of SB I was hooked. I really love the flexibility, the look, the feel of that app.

But I was most impressed from the concept of “everything is an Extension/Plug/YouNameIt”

This architectural choice opens so many options.

I like this approach so much, because I’m coming from the use of a completely different software, with a similar design goal: [[ikiwiki.info|IkiWiki]]

Ikiwiki is an StaticSiteGenerator, thats much older than hugo or the like. Still it already was based on a templating language (and perl) and generated quite some large sites.

Ikiwiki also realized a lot of the functionality through external plugins. And lots of plugins it has.
It also is based on Markdown as user input, and it could also link between different pages in a very sophisticated manner.

But it had indeed quite some more useful features realized, than there currently are in SilverBullet. But this is no complaining. Its because of the age, because, IkiWiki had the chance to grow and to mature to the beast it is. But it is chained to its development roots and has grown in its language, SB is young and I can see a future where quite some of the features are available in an equivalent or better way. The interactivity which SB offers is such an incredible win, that Iki never was able to give, because of its architecture.

Thats why I’m thinking of gathering some ideas and creating some issues tickets, to explain, and help implementing these features.

So, most of the issues I’ll be opening the next days/weeks will be some, that allow to close some gaps and provide a functionality that surpasses the idea of a “simple note taking” app ... ;)

I have a list of these ideas published under https://github.com/jwalzer/SilverBulletSandbox/tree/main/silverbullet/issues where I’m currently trying to play with the options that SB gives
<!-- /include -->
___

### Issuelist
<!-- #query page where name =~ /silverbullet\/issues\/.*/ render [[template/pagelist/silverbullet]] -->
* [[silverbullet/issues/Keyboard Shortcut for Updates]]
  * some keyboard shortcuts are not well selected

* [[silverbullet/issues/Variable Expansion inside page]]
  * Allow expansion of variables inside the page via handlebars

* [[silverbullet/issues/Selective Include]]
  * Allow for include to only include specific parts of a page

* [[silverbullet/issues/Virtual pages]]
  * generate "virtual" pages for empty directories

* [[silverbullet/issues/Header, Footer, SidePage]]
  * Having Headers, Footers and the Sidepage defined

* [[silverbullet/issues/Ellipsis and folding]]
  * Directive to allow folding/ellipsis of a section

* [[silverbullet/issues/Per Directory Settings]]
  * some settings should be possible to overwrite on a directory basis
<!-- /query -->

### Open Tasks

<!-- #query task where page =~ /^silverbullet.*/ and done = false render [[template/tasks/silverbullet]]-->

<!-- /query -->
