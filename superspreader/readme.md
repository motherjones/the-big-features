# [Superspreader in Chief](https://www.motherjones.com/politics/2020/10/trump-coronavirus-covid-denial-timeline/)


### Source code:
- [HTML](post-body.html)
- [CSS](custom-css.css)

### Shortcodes used:
- `[timeline-filters]`
- `[filter]`
- `[timeline]`
- `[slides]`
- `[slide]`

### Shortcode reference:
- [Docs site](https://docs.motherjones.com/2019/06/27/shortcodes/)

### Notes:
- The custom font, "Tandelle," is loaded via an `@import` statement in the Custom CSS field.
- There's an extra script tag at the bottom of the post body that forces the 100 Days video (https://youtu.be/MaUoeVt5bHg) into the succeeding timeline box. This is necessary because the timeline shortcode doesn't support oembed videos within it. (This was a late, post-pub addition. I'm unsure why no one wanted to put the video outside of a box, but here we are.) For this little script to work, the youtube link needs to be on its own line in the editor: 
```
<div class="mjtl-item like-p grid down magic milestone">
https://youtu.be/MaUoeVt5bHg
</div>
```