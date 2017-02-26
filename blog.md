---
layout: page
title: Blog
permalink: /Blog
---
<!--
Some information about you!

### More Information

A place to include any other types of information that you'd like to include about yourself.

### Contact me

[cvghy116@gmail.com](mailto:cvghy116@gmail.com)
-->

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
