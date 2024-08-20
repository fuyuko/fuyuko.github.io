---
layout: default
title: Travel
---
<div id="archives">
{% for category in site.categories %}
  <div class="archive-group">
    {% capture category_name %}{{ category | first }}{% endcapture %}
    <div id="#{{ category_name | slugize }}"></div>
        <h2 class="category-head">{{ category_name }}</h2>
        <a name="{{ category_name | slugize }}"></a>
        {% for post in site.categories[category_name] %}
            <article class="archive-item">
            <h5><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h5>  
            {{ post.excerpt }}
            </article>
        {% endfor %}
    </div>
{% endfor %}
</div>