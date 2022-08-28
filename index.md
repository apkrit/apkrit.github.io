---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
permalink: /
---

<div class="homesplash">
  {{ page.homesplash_text }}
  <img class="feature-img" src="{{ 'assets/images/img1.jpg' | relative_url }}" />
</div>
<!-- ![home splash1]({{ site.url }}/assets/images/img1.jpg) -->

/* Cover Image */
.homesplash {
  background: url(assets/images/img1.jpg);
}