---
layout: default
title: Travel
---
<div id="archives">
        <div class="archive-group">
            {% capture category_name %}travel{% endcapture %}
            <div id="#travel"></div>
            <h2 class="category-head">travel</h2>
            <a name="travel"></a>
            {% for post in site.categories['travel'] %}
                <article class="archive-item">
                    <h3><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h3>  
                    <div class="thumbnail">
                        <img src="{{ site.baseurl }}/images/{{ post.thumbnail }}" alt="thumbnail image for {{post.title}}"/>
                    </div>
                    {{ post.excerpt }}
                </article>
            {% endfor %}
        </div>
</div>