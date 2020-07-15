---
layout: page
title: Welcome to the Bergland Lab
subtitle: an ecological- and evolutionary-genetics lab
hero_height: is-large
hero_link: /#callouts
hero_link_text: Scroll for more
show_sidebar: false
callouts: homepage_callouts
---
<!-- set up scroll elements for the announcements -->
<style>
.scroll_wrapper {
    position: relative;
    display: inline-block;
    padding-right: 10px;
    margin-top: -12px;
    width: 100%;
    height: 50%;
}
.scroll {
    overflow-x: scroll;
    overflow-y: hidden;
    white-space: nowrap;
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
