---
layout: page
title: "Staff"
show_meta: false
permalink: "/staff/"
header:
    image_fullwidth: "header_drop.jpg"
---
<div class="row">
    <div class="medium-12 columns">
      {% for post in site.staff %}
      <a href="{{ site.url }}{{ post.url }}" class="category"><h2>{{ post.title }}</h2>
      <p>
      {% if post.position %}<span>{{ post.position }}<br></span>{% endif %}
      {% if post.telephone %}<span>Tel: {{ post.telephone }}<br></span>{% endif %}
      {% if post.email %}<span><a href="mailto:{{ post.email }}">{{ post.email }}</a><br></span>{% endif %}
      </p>
      {% endfor %}
    </div>
</div>
