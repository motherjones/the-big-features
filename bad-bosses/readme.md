# [Bad Bosses](https://www.motherjones.com/politics/2021/09/bad-bosses-workers-fought-back-asshole-managers-nurse-guard-amazon-microsoft/)


### Source code:
- [HTML](post-body.html)
- [CSS](custom-css.css)

### Shortcodes used:
- `[cards]`
- `[card]`
- `[include-post]`
- `[in-content]`

### Shortcode reference:
- [Docs site](https://docs.motherjones.com/2019/06/27/shortcodes/)

### Notes:
- The custom font, "Balboa," is loaded via an `@import` statement in the Custom CSS field.
- To achieve the extra-long (and extra sharp) cover art, we hide the default title image and add two background images to the entry header (one to the header itself and another to its :after pseudoclass). To make it responsive, we change the background-size property in a series of media queries.
- Although the title image doesn't display, the post needs to have one set under "Title Image (Portrait)" in order to have the slim navbar.
- The `header.entry-header:after` selector has a base-64 transparent pixel in its "content" property because the Custom CSS field encodes quotation marks so we couldn't use an empty tring for the value of "content".