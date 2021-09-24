# [Anxious? Furious? Hopeful? So Are We.](https://www.motherjones.com/politics/2020/11/come-feel-election-day-feelings-with-mother-jones-staff/)


### Source code:
- [HTML](post-body.html)
- [CSS](custom-css.css)

### Shortcodes used:
- `[timeline-filters]`
- `[filter]`
- `[timeline]`
- `[include-post]`
- `[backtotop]`

### Shortcode reference:
- [Docs site](https://docs.motherjones.com/2019/06/27/shortcodes/)

### Notes:
- The custom font, "Tandelle," is loaded via an `@import` statement in the Custom CSS field.
- We override the default filter emojis in Custom CSS like so:
```
#mjtl-filter #mjtl-anxious+label span {
     background-image: url(https://www.motherjones.com/wp-content/uploads/2020/10/election-emojis-anxious.png?w=150);
}
 #mjtl-filter #mjtl-furious+label span {
     background-image: url(https://www.motherjones.com/wp-content/uploads/2020/10/election-emojis-furious.png?w=150);
}
 #mjtl-filter #mjtl-hopeful+label span {
     background-image: url(https://www.motherjones.com/wp-content/uploads/2020/10/election-emojis-hopeful.png?w=150);
}
```