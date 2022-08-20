---
layout: page
title: About this theme
---

### Supported layouts

This theme supports following layouts for writing;

- `page` - For static page, e.g. this page.
- `post` - Layout for writing your essay, or blog post. _You should focus here._

### Captioned image

This theme implements `include` tag where you can use in your markdown to insert an image that has a caption.

Example:

{% raw %}
```liquid
{%
    include figure.html 
    src="https://i.imgur.com/7yOUCeG.jpg" 
    caption="Fossil Creek Reservoir, Fort Collins, CO (<a href='https://heiswayi.nrird.com/photography'>source</a>)"
    href="https://heiswayi.nrird.com/photography"
%}
```
{% endraw %}

### Navigation and footer

- `_includes\header.html` - You may edit your site navigation here.
- `_includes\footer.html` - You may edit your footer, or site copyright here.
