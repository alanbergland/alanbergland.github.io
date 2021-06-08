---
layout: page
title: Welcome to the Bergland Lab
subtitle: ecological and evolutionary genetics
hero_height: is-medium
show_sidebar: false
---
<!-- set up scroll elements for the announcements -->
<style>
.scroll_wrapper {
    position: relative;
    width: 100%;
    height: 50%;
    overflow-x: auto;
    white-space:nowrap;
}
.scroll {
    display:inline-block;
    width: 40%;
    height: 50%;
    white-space: normal;
    padding:0 10px 10px 10px;
}
</style>

# Recent Announcements
<div class="scroll_wrapper">
  {% for post in site.posts %}
  <div class="scroll">
        {% include post-card.html %}
  </div>
  {% endfor %}
</div>
