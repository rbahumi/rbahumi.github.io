---
layout: post
comments: true
title:  "Deep Learning - Cross Entropy Loss Derivative"
date:   2019-09-05 00:07:15 +0200
categories: "deep_learning"
---

<style>
.wrapper {
    max-width: -webkit-calc(1200px - (30px * 2));
    max-width: calc(1200px - (30px * 2));
}
</style>

<!--<object data="{{site.baseurl}}/pdfs/cross_entropy_loss_derivative.pdf" width="1000" height="1000" type='application/pdf'></object>-->

{% include notebook_imports.html %}
<link rel="stylesheet" href="{{ site.baseurl }}/css/my.css">
<link rel="canonical" href="{{ site.production_url }}{{ post.url | replace:'index.html',''}}">

{% include cross_entropy_loss_derivative.html %}


{% if page.comments %}
    {% include disqus.html %}
{% endif %}
