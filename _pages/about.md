---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>
{% include_relative includes/intro.md %}

<!-- If you like the template of this homepage, welcome to star and fork my open-sourced template version [AcadHomepage ![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io?style=social)](https://github.com/RayeRen/acad-homepage.github.io). -->

<!-- {% include_relative includes/news.md %} -->

<span class='anchor' id='research-tabs'></span>
<div class="content-switcher">
  <div class="content-switcher__tabs">
    <a class="content-switcher__tab is-active" href="#papers" data-tab-target="papers">发表论文</a>
    <a class="content-switcher__tab" href="#competitions" data-tab-target="competitions">科研竞赛</a>
  </div>

  <div class="content-switcher__panel is-active" data-tab-panel="papers">
    {% include_relative includes/pub.md %}
  </div>

  <div class="content-switcher__panel" data-tab-panel="competitions">
    {% include_relative includes/honers.md %}
  </div>
</div>
