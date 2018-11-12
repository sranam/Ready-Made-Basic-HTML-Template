Ready Made Starter HTML Template based on [HTML5 Boilerplate homepage](https://html5boilerplate.com/) | [Documentation
table of contents](TOC.md)

# The CSS

Ready Made Starter HTML Template's CSS includes:

* [Normalize.css](#normalizecss)
* [CSS Header](#css-header)
* [CSS Table of contents](#css-table-of-contents)
* [General CSS](#general-css)
* [WordPress Specific CSS](#wordpress-specific-css)
* [Common helpers](#common-helpers)
* [Position abosolute fixing](#position-abosolute-fixing)
* [Input placeholder text cross broser CSS](#Input-placeholder-text-cross-broser-css)
* [Print styles](#print-styles)
* [Responsive.css](#responsivecss)

This starting CSS does not rely on the presence of
[conditional class names](https://www.paulirish.com/2008/conditional-stylesheets-vs-css-hacks-answer-neither/),
[conditional style sheets](https://css-tricks.com/how-to-create-an-ie-only-stylesheet/),
or [Modernizr](https://modernizr.com/), and it is ready to use no matter what
your development preferences happen to be.


## Normalize.css

In order to make browsers render all elements more consistently and in line
with modern standards, we include
[Normalize.css](https://necolas.github.io/normalize.css/) — a modern, HTML5-ready
alternative to CSS resets.

As opposed to CSS resets, Normalize.css:

* targets only the styles that need normalizing
* preserves useful browser defaults rather than erasing them
* corrects bugs and common browser inconsistencies
* improves usability with subtle improvements
* doesn't clutter the debugging tools
* has better documentation

For more information about Normalize.css, please refer to its [project
page](https://necolas.github.com/normalize.css/), as well as this
[blog post](http://nicolasgallagher.com/about-normalize-css/).

## CSS Header

In CSS header you can find some info related to the theme. It is mandatory for Themeforest standard WordPress theme. You should replace the info with yours.

## CSS Table of contents

Developers find it handy as they can  reach any of the CSS section very easily using it. Moreover, it is recommended for Themeforest standard HTML template/WP theme. Here are some place holder content items. Developers must replace these with theirs.

## HTML5 Boilerplate v6.1.0 CSS

Several base styles are included that build upon `Normalize.css`. These
styles:

* provide basic typography settings that improve text readability
* protect against unwanted `text-shadow` during text highlighting
* tweak the default alignment of some elements (e.g.: `img`, `video`,
  `fieldset`, `textarea`)
* style the prompt that is displayed to users using an outdated browser

You are free and even encouraged to modify or add to these base styles as your
project requires.

## GENERAL CSS STYLE

Here you can find some common CSS style which can be used throughout the websites.

You are free and even encouraged to modify or add to these base styles as your
project requires.

## WORDPRESS SPECIFIC CSS 

Here is some WordPress specific CSS which is a must for Themeforest standard WordPress theme. And of course, you can use the class for any of your design whether it is CMS based or not.

## Common helpers

Along with the base styles, we also provide some commonly used helper classes.

#### `.hidden`

The `hidden` class can be added to any element that you want to hide visually
and from screen readers. It could be an element that will be populated and
displayed later, or an element you will hide with JavaScript.

#### `.visuallyhidden`

The `visuallyhidden` class can be added to any element that you want to hide
visually, while still have its content accessible to screen readers.

See also:

* [CSS in Action: Invisible Content Just for Screen Reader
  Users](https://webaim.org/techniques/css/invisiblecontent/)
* [Hiding content for
  accessibility](https://snook.ca/archives/html_and_css/hiding-content-for-accessibility)
* [HTML5 Boilerplate - Issue #194](https://github.com/h5bp/html5-boilerplate/issues/194).

__N.B.__ [The visuallyhidden class can be an accessibility issue for users using high contrast modes.](https://www.paciellogroup.com/blog/2012/08/notes-on-accessible-css-image-sprites/)

>Use JavaScript to detect when images are disabled and remove the CSS visually hidden display state of the text alternative.
Use JavaScript to detect when Windows high contrast mode is enabled and remove the CSS visually hidden display state of the text alternative.

#### `.invisible`

The `invisible` class can be added to any element that you want to hide
visually and from screen readers, but without affecting the layout.

As opposed to the `hidden` class that effectively removes the element from the
layout, the `invisible` class will simply make the element invisible while
keeping it in the flow and not affecting the positioning of the surrounding
content.

__N.B.__ Try to stay away from, and don't use the classes specified above for
[keyword stuffing](https://en.wikipedia.org/wiki/Keyword_stuffing) as you will
harm your site's ranking!

#### `.clearfix`

The `clearfix` class can be added to any element to ensure that it always fully
contains its floated children.

Over the years there have been many variants of the clearfix hack, but currently,
we use the [micro clearfix](http://nicolasgallagher.com/micro-clearfix-hack/).


## Position abosolute fixing for chrome, safari and opera css

This is a media query to fix the issue with position absolute style for Chrome, Safari and Opera.

## Input placeholder text cross broser CSS

This CSS will fix the problem input placeholder text color etc. for the browsers.


## Print styles

Lastly, we provide some useful print styles that will optimize the printing
process, as well as make the printed pages easier to read.

At printing time, these styles will:

* strip all background colors, change the font color to black, and remove the
  `text-shadow` — done in order to [help save printer ink and speed up the
  printing process](http://www.sanbeiji.com/archives/953)
* underline and expand links to include the URL — done in order to allow users
  to know where to refer to<br>
  (exceptions to this are: the links that are
  [fragment identifiers](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attr-href),
  or use the
  [`javascript:` pseudo protocol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/void#JavaScript_URIs))
* expand abbreviations to include the full description — done in order to allow
  users to know what the abbreviations stands for
* provide instructions on how browsers should break the content into pages and
  on [orphans/widows](https://en.wikipedia.org/wiki/Widows_and_orphans), namely,
  we instruct
  [supporting browsers](https://en.wikipedia.org/wiki/Comparison_of_layout_engines_%28Cascading_Style_Sheets%29#Grammar_and_rules)
  that they should:

  * ensure the table header (`<thead>`) is [printed on each page spanned by the
    table](http://css-discuss.incutio.com/wiki/Printing_Tables)
  * prevent block quotations, preformatted text, images and table rows from
    being split onto two different pages
  * ensure that headings never appear on a different page than the text they
    are associated with
  * ensure that
    [orphans and widows](https://en.wikipedia.org/wiki/Widows_and_orphans) do
    [not appear on printed pages](https://css-tricks.com/almanac/properties/o/orphans/)

The print styles are included along with the other `css` to [avoid the
additional HTTP request](http://www.phpied.com/delay-loading-your-print-css/).
Also, they should always be included last, so that the other styles can be
overwritten.

## responsive.css

We used an individual file to make the site responsive for several devices. You can make your customized responsive as you needed. The responsive-breakpoints.txt file (within assets directory) will help you in this regard.
