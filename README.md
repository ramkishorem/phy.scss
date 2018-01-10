# phy.scss - A Sass Framework/Skeleton

phy.scss is a Sass (scss syntax) based, Object Oriented Framework(more like a Skeleton) built with objects and abstractions that I usually use for my websites.

## OOCSS

phy.scss is an object-oriented(OO) skeleton that focuses on providing design patterns and abstractions rather than actual designs. OOCSS promotes DRYness, reuse, portability and lends itself well to scalability, which makes writing css for projects of any size a lot easier.

## Who is it for?

Any developer/designer who understands the need for abstraction and OO approach can pick this as a starting point to make their own skeleton.

## What should I know?

A good css knowledge is needed, obviously. On top of that, a basic understanding of oops is needed to grasp the code structure that is involved and has to be maintained.

## Installation

**Requires Sass >=3.2**

Installation is pretty simple. Download a zip of the project and extract into a folder, say sass, alongside your css folder. 

    your-project-folder/
        css/
        	style.min.css
        sass/
        	nuclie/
        	properties/
        	quarks/
            atoms/
            molecules/
            phy.scss
            watch
        index.html
        
This is not a necessity. But the watch files provided with the framework assume this structure. If you put the sass elsewhere, modify the watch file, accordingly. Watch files for both windows cmd prompt and unix terminal are included.


## Document

There won't be a separate document for phy.scss. But I consider the code to be my document. All the modules are commented heavily either by me or by people from whom I forked few modules.

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


License
The MIT License (MIT)

Copyright (c) 2012-2017 Ramkishore M

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.