---
layout: default
title: Blog
permalink: "/blog/"

---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <!--<h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>-->

      <div class="entry">
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.excerpt }}<DIV CLASS="postTitle">{{ post.title }}</DIV></a>
      </div>

      <!--<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>-->
    </article>
  {% endfor %}
</div>

