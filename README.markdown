# Dichotomy

![](screenshots/default.png)

**Dichotomy** is a minimalistic theme built around high-contrast boxes
and the reassuring, regular grid of monospaced fonts.
It comes with built-in mobile styles, support for HTML5 sectioning and
semantic elements like `<article>` and `<time>`, and a whole bunch of
customizable appearance options.

This theme was written by [Kevin Xiwei Zheng](https://room208.org/),
and is released into the public domain according to the [Creative
Commons Zero](http://creativecommons.org/publicdomain/zero/1.0/)
dedication.
I waive all copyright and related or neighboring rights to this work to
the extent possible under law.
Although there is no requirement to do so, I'd appreciate a link back to
this page if you use or create any derivatives of Dichotomy.
Thanks!

Got a feature request or bug fix?
Visit [Dichotomy on GitHub](https://github.com/kxz/dichotomy).
Note that all code contributions must be released under CC0.
The `master` branch holds the latest release,
while `develop` contains changes scheduled for the next one.


## Installation

Log in to Tumblr, then visit [Dichotomy's Theme Garden
page](http://www.tumblr.com/theme/38335) and click on the *Install*
button.


## Appearance options

### Custom colors

The theme's various colors can be changed using the standard selectors.
Use the *Midground Opacity* text field to adjust the background opacity
of block quotes and the like; values range from 0.0 to 1.0.

### Background images

Dichotomy can use your Tumblr header image as a custom page background.
Just enable the *Header Image as Background* option.

### Mobile and left-handed layouts

In order to use Dichotomy's mobile styles, you must first disable
Tumblr's default ones by going to *Advanced options* and unchecking *Use
optimized mobile layout*.

By default, on large displays, Dichotomy shows scrolling posts on the
left side and fixed navigation on the right.
You can change this using the *Desktop Layout* option.
*Left-Handed* flips the default layout, while *Mobile* always uses the
centered mobile styles with a larger font, even on larger screens.

Note that Tumblr's teasers for users that are not logged in were not
designed to be displayed on the left, and might look misaligned if you
use the left-handed layout.
You can always uncheck the *Promote Tumblr* option under *Advanced
options* if this bothers you.

### Subtitle and copyright author

Any text entered in the *Subtitle* field will appear in the title bar on
the index page, and next to your blog's name in the page header.
If you provide a *Copyright Author*, it will also appear in the header
as part of a copyright statement.

### Header backlink

If your blog is part of a larger site, you can include a backlink to
that site in the page header by filling in the *Backlink URL* and
*Backlink Title* fields.
The backlink will appear as the first of your navigation links.

### Google Analytics

If you have a Google Analytics account, just enter your tracking ID into
the provided field, and set the *GA Universal Tracking* option according
to your analytics configuration.
(For most new Google Analytics users, Universal Tracking should be
enabled.)
Dichotomy will include the required JavaScript for you.

### Automatic syntax highlighting

Post a lot of code?
Turn on syntax highlighting, and Dichotomy will use
[highlight.js](http://softwaremaniacs.org/soft/highlight/en/)
to automatically color code snippets inside
`<pre><code>...</code></pre>` tags.
(This is the default wrapping for Markdown indented code blocks.)
