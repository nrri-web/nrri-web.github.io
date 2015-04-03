---
layout: page
title: "Job Opportunities"
show_meta: false
permalink: "/jobs/"
header:
    image_fullwidth: "header_drop.jpg"
---
<div class="row">
    <div class="medium-12 columns">
      {% for post in site.jobs %}
      <h2>{{ post.title }}</h2>
      <p>
      {{ post.content }}
      </p>
      {% endfor %}
    </div>
</div>
