# CSS Grid
After 5 years of working on the specification for CSS Grid, major browsers
(but not IE and Edge fully...) have released support to use CSS Grid in March
2017. It will also gracefully fallback nicely to flexbox, inline-block and so
on. So why wait!?

## CSS Grid Example 1
In the first example of using CSS Grid I'll show you a quick demo of how a
common website layout might look with the use of `grid-area` and
`grid-template-areas` property.

It consists of a header, nav, main content, article, sidebar and footer on a
12 column layout.

It is also restricted to a width of 960px and centered on the page.

## CSS Grid Example 2
Same as Example 1 but the nav is embedded into the header and using more
properties that comes with CSS grid, which include `grid-column-start`,
`grid-column-end` and the `span` value.

## When to use Flexbox and Grid?
Flexbox is one dimensional which is good for presenting your content either in
a row OR a column, and you want to distribute space.

If you find yourself defining the width of each item of your flexbox then grid
is the way to go. Grid is two dimensional so you can control both row and column
from the parent. Also as seen in Example 2 the nav section overlapped with the
header section. 

## Links
For more information, check out this link
https://css-tricks.com/snippets/css/complete-guide-grid/

And this very cool game that helps you get to grips with the CSS grid syntax
http://cssgridgarden.com/

Of course, don't forget the MDN documentation!
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout

And the specification:
https://www.w3.org/TR/css3-grid-layout/

Happy reading!!!
