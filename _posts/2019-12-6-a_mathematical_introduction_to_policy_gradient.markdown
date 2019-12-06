---
layout: post
comments: true
title:  "Reinforcement Learning - A mathematical introduction to Policy Gradient"
date:   2019-12-06 12:07:15 +0200
categories: ["deep_learning", "reinforcement_learning"]
---

<style>
.wrapper {
    max-width: -webkit-calc(1200px - (30px * 2));
    max-width: calc(1200px - (30px * 2));
}
</style>

{% include notebook_imports.html %}
<link rel="stylesheet" href="{{ site.baseurl }}/css/my.css">
<link rel="canonical" href="{{ site.production_url }}{{ post.url | replace:'index.html',''}}">

{% include policy-gradient-from-a-gradient-perspective.html%}


{% if page.comments %}
    {% include disqus.html %}
{% endif %}
