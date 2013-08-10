# phy.scss - A Sass Framework/Skeleton

phy.scss is a Sass (scss syntax) based, Object Oriented Framework built with objects and abstractions that I usually use for my websites. 

The skeleton focuses on providing a design pattern rather than actual designs. I built it as a way to get started with styling quickly but still with a clean slate for every webstie. Sticking to this folder/module structure also helps with keeping the css clean and easily maintainable.

Any developer who understands the need for abstraction and OO approach can pick this as a starting point to make their own skeleton.

There won't be a separate document for phy.scss. But I consider the code to be my document. All the modules are commented heavily either by me or by people from whom I forked few modules.

## Installation

**Requires Sass >=3.2**

Installation is pretty simple. Download a zip of the project and extract into a folder, say sass, alongside your css folder. This is not a necessity. But the watch files provided with the framework assume this structure. If you put the sass elsewhere, modify the watch file, accordingly. Watch files for both windows cmd prompt and unix terminal are included.


## Document

Treat the phy.scss file as a list of contents. That file imports all the modules and brings everything together. If I don't need any of the modules in the skeleton for a particular project, I simply comment it out. In fact, I usually start with commenting all the atoms and molecules. Some of the bigger modules depend on objects in the smaller ones. But you can figure out any missing modules when sass throws related errors.


## Inpired by

I'll list my inspirations in the order of my exposure to them.

* [Our (CSS) Best Practices Are Killing US](http://www.stubbornella.org/content/2011/04/28/our-best-practices-are-killing-us/) - Article by Nicole Sullivan.
* [OOCSS](http://oocss.org/) - by Nicole Sullivan
* [Principles of writing consistent, idiomatic CSS](https://github.com/necolas/idiomatic-css) - CSS writing - by Nicolas Gallager
* [Breaking good habits](http://csswizardry.com/2012/07/video-breaking-good-habits-front-trends-2012/) - video presentation by Harry Roberts
* [MindBEMding – getting your head ’round BEM syntax](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/) - Article by by Harry Roberts
* [inuit.css](https://github.com/csswizardry/inuit.css) - csswizardy's sass framework. phy.scss is basically a mangled fork of this repo tailored to my needs
* [The “Other” Interface: Atomic Design With Sass](http://coding.smashingmagazine.com/2013/08/02/other-interface-atomic-design-sass/) - Smashing Magazine article by Robin Rendle. This article inspired my folder names and the module structure.

