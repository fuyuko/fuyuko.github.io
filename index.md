---
layout: default
---
<div id="archives">
{% for post in site.posts limit:10 %}
    <article class="archive-item">
        <h3><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h3>  
        <div class="thumbnail">
            <img src="{{ site.baseurl }}/images/{{ post.thumbnail }}" />
        </div>
        {{ post.excerpt }}
    </article>
{% endfor %}
</div>

