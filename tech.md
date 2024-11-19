---
layout: default
title: Tech
---
<div id="archives">
        <div class="archive-group">
            {% capture category_name %}tech{% endcapture %}
            <div id="#tech"></div>
            <h2 class="category-head">tech</h2>
            <a name="tech"></a>
            {% for post in site.categories['tech'] %}
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