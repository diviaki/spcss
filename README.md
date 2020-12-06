SPCSS
=====

SPCSS is a simple and plain stylesheet for simple text-based websites.

[![View Demo][Demo SVG]][Demo URL]
[![View CSS][CSS SVG]][CSS URL]
[![NPM Version][Version SVG]][NPM URL]
[![MIT License][License SVG]][L]
[![Twitter][Twitter SVG]][Twitter URL]

Note: A demo page is available [here][Demo URL].

[Demo SVG]: https://img.shields.io/badge/view-demo-brightgreen.svg
[Demo URL]: https://susam.github.io/spcss/

[CSS SVG]: https://img.shields.io/badge/view-sp.css-brightgreen.svg
[CSS URL]: https://susam.github.io/spcss/sp.css

[Version SVG]: https://img.shields.io/npm/v/spcss.svg
[NPM URL]: https://www.npmjs.com/package/spcss

[License SVG]: https://img.shields.io/badge/license-MIT-%233ea639
[L]: LICENSE.md

[Twitter SVG]: https://img.shields.io/badge/twitter-%40susam-%231da1f2
[Twitter URL]: https://twitter.com/susam


Contents
--------

* [Use SPCSS](#use-spcss)
* [CDN URLs](#cdn-urls)
* [Why SPCSS?](#why-spcss)
* [Features](#features)
* [License](#license)
* [Support](#support)


Use SPCSS
---------

To use SPCSS, merely add this line of code to the `<head>` element of
your HTML file:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/spcss@0.3.0">
```

Alternatively, download the CSS file from [here][DL], edit and customize
it as per your requirements, and use it in your project. You are also
welcome to [fork this repository][fork] and customize it to maintain
your own copy of [sp.css](sp.css) with styles you frequently need.

[DL]: https://cdn.jsdelivr.net/npm/spcss@0.3.0/sp.css
[fork]: https://github.com/susam/spcss/fork


CDN URLs
--------

Use the following URL in the `<link>` tag to load version 0.3.0 (the
current version at this time) of SPCSS:

```
https://cdn.jsdelivr.net/npm/spcss@0.3.0
```

Use the following URL in the `<script>` tag to always load the latest
version of SPCSS:

```
https://cdn.jsdelivr.net/npm/spcss
```

If you need something really easy to remember, use this URL to load the
latest version of SPCSS:

```
https://unpkg.com/spcss
```


Why SPCSS?
----------

I often develop primarily text-based websites and webpages. The default
style chosen by the web browsers while decent leaves a bit to be
desired, so I often add a minimal stylesheet to improve the apperance of
the document, hyperlinks, code blocks, blockquotes, etc. This project
shares the minimal stylesheet that I often rely on for styling simple
websites and webpages.

You are welcome to [fork this repository][fork] and customize it to
maintain your own copy of [sp.css](sp.css) with styles that you
frequently need.


Features
--------

Here is a summary of the style changes provided by SPCSS:

- Maximum width for the `<body>` element to prevent the lines from being
  too long. Shorter lines make it easier for our eyes to gauge the
  beginning and end of the lines.
- Dark gray (`#333`) text color instead of black (`#000`).
- Increased line-height to add more room around the lines and make them
  easier to read.
- More margin above headings to separate them more conspicuously from
  preceding content.
- Less margin below headings as well as less `line-height` for margins
  to associate them more tightly with succeeding content.
- Consistent blue color for hyperlinks throughout the content with the
  exception of headings (see next point).
- Retain dark gray text color for headings even when the headings are
  hyperlinks.
- Ensure width of images do not exceed the maximum width for the
  `<body>` element.
- Simple styling for `<figure>` and `<figcaption>` elements such as
  margins aligned with the margins of text paragraphs, centered
  captions, reduced font size for captions.
- Light gray background for code blocks and blockquotes.
- Prevent very long lines of code from overflowing outside the gray box
  for code blocks. Instead, make the code block scrollable when the code
  overflows the gray box.

See [this example page][Demo URL] for a quick demonstration of some of
these features.


License
-------

This is free and open source software. You can use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of it,
under the terms of the MIT License. See [LICENSE.md][L] for details.

This software is provided "AS IS", WITHOUT WARRANTY OF ANY KIND,
express or implied. See [LICENSE.md][L] for details.

[L]: LICENSE.md


Support
-------

To report bugs, suggest improvements, or ask questions,
[create issues][ISSUES].

[ISSUES]: https://github.com/susam/spcss/issues
