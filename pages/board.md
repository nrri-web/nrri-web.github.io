---
layout: page
title: "Board of Directors"
show_meta: false
permalink: "/board/"
header:
    image_fullwidth: "header_drop.jpg"
---
<div class="row">
    <div class="medium-12 columns">
      {% for post in site.board %}
      {% if post.board_position == "chair" %}
      <a href="{{ site.url }}{{ post.url }}" class="category"><h2>{{ post.title }}</h2>
      <p>
      {% if post.position %}<span>{{ post.position }}<br></span>{% endif %}
      {% if post.term_ends %}<span>{{ post.term_ends }}<br></span>{% endif %}
      {% if post.address %}<span>{{ post.address }}<br></span>{% endif %}
      {% if post.telephone %}<span>Tel: {{ post.telephone }}<br></span>{% endif %}
      {% if post.email %}<span><a href="mailto:{{ post.email }}">{{ post.email }}</a><br></span>{% endif %}
      </p>
      {% endif %}
      {% endfor %}
      {% for post in site.board %}
      {% if post.board_position == "vice-chair" %}
      <a href="{{ site.url }}{{ post.url }}" class="category"><h2>{{ post.title }}</h2>
      <p>
      {% if post.position %}<span>{{ post.position }}<br></span>{% endif %}
      {% if post.term_ends %}<span>{{ post.term_ends }}<br></span>{% endif %}
      {% if post.address %}<span>{{ post.address }}<br></span>{% endif %}
      {% if post.telephone %}<span>Tel: {{ post.telephone }}<br></span>{% endif %}
      {% if post.email %}<span><a href="mailto:{{ post.email }}">{{ post.email }}</a><br></span>{% endif %}
      </p>
      {% endif %}
      {% endfor %}
      {% for post in site.board %}
      {% if post.board_position == "treasurer" %}
      <a href="{{ site.url }}{{ post.url }}" class="category"><h2>{{ post.title }}</h2>
      <p>
      {% if post.position %}<span>{{ post.position }}<br></span>{% endif %}
      {% if post.term_ends %}<span>{{ post.term_ends }}<br></span>{% endif %}
      {% if post.address %}<span>{{ post.address }}<br></span>{% endif %}
      {% if post.telephone %}<span>Tel: {{ post.telephone }}<br></span>{% endif %}
      {% if post.email %}<span><a href="mailto:{{ post.email }}">{{ post.email }}</a><br></span>{% endif %}
      </p>
      {% endif %}
      {% endfor %}
      {% for post in site.board %}
      {% if post.board_position == "secretary" %}
      <a href="{{ site.url }}{{ post.url }}" class="category"><h2>{{ post.title }}</h2>
      <p>
      {% if post.position %}<span>{{ post.position }}<br></span>{% endif %}
      {% if post.term_ends %}<span>{{ post.term_ends }}<br></span>{% endif %}
      {% if post.address %}<span>{{ post.address }}<br></span>{% endif %}
      {% if post.telephone %}<span>Tel: {{ post.telephone }}<br></span>{% endif %}
      {% if post.email %}<span><a href="mailto:{{ post.email }}">{{ post.email }}</a><br></span>{% endif %}
      </p>
      {% endif %}
      {% endfor %}
      {% for post in site.board %}
      {% unless post.board_position %}
      <a href="{{ site.url }}{{ post.url }}" class="category"><h2>{{ post.title }}</h2>
      <p>
      {% if post.position %}<span>{{ post.position }}<br></span>{% endif %}
      {% if post.term_ends %}<span>{{ post.term_ends }}<br></span>{% endif %}
      {% if post.address %}<span>{{ post.address }}<br></span>{% endif %}
      {% if post.telephone %}<span>Tel: {{ post.telephone }}<br></span>{% endif %}
      {% if post.email %}<span><a href="mailto:{{ post.email }}">{{ post.email }}</a><br></span>{% endif %}
      </p>
      {% endunless %}
      {% endfor %}
    </div>
</div>
