---
title: About
layout: page
permalink: "/about/"
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## Some heading 

Oh, hello.
I'm Simone but call me Soxa. I'm just a new programmer and this is my blog.
Using GitHub Pages with Jekyll.

</div>