---
layout: page
title: 博客
---
<div class="category">
    <ul>
    {% for post in site.categories.blog %}
        <li>
            <h2>
            	<a href="{{ post.url }}">{{ post.title }}</a>
            </h2>
            <span>{{ post.description }}</span>
        </li>
    {% endfor %}
    </ul>
</div><!-- .entry -->
