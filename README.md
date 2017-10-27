# csstdg4figs

This repository contains the files used to create the figures for [_CSS: The Definitive Guide, 4th Edition_](http://shop.oreilly.com/product/0636920012726.do).  I mostly did this by loading them up in Firefox OS X and using the `screenshot` command-line utility (see “[Essential Tool: Firefox’s screenshot Command](http://meyerweb.com/eric/thoughts/2015/10/22/firefoxs-screenshot-command/)” for more information)—except in the rare cases where Firefox didn’t support the thing I was illustrating, in which case I used Chrome OS X set to somewhere around 200% zoom.

## Notes

* If you want an easy-to-browse method of access, load the repo-root-level `index.html` in a web browser and surf from there.  Also [available on GitHub Pages](https://meyerweb.github.io/csstdg4figs/).
* Each chapter’s page lists all of the figures’ captions in the order they appear in the book.  Where a caption is a link, it leads to the files used to create the figure in question.  Where it’s unlinked text, there are no files to see.  (Thus: if a figure is a diagram that wasn’t created in-browser, or the files were lost, or it was judged not to be useful in a browser setting, it will be listed but not linked.)
* Chapters 17 and 18 (“Transitions” and “Animations”) have extra examples that do not correspond to figures in the book, but are instead referenced from within the book using small “push play” icons.  This is how we dealt with the difficulty of illustrating animations in print.
* What you see in your browser may or may not match what’s shown in the book’s figure.  I have made essentially no effort to vendor-prefix or otherwise work around cross-browser limitations, except where doing so was germane to the content in the actual book.  When in doubt, see the book for compatibility information.
* The styling of the index pages uses, as much as reasonable, new features of CSS in a progressively-enhancing way.  So don’t forget to view source and poke around in the `styles` directory!