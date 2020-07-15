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
}
.scroll {
    overflow-x: scroll;
    overflow-y: hidden;
    height: 800px;
    white-space: nowrap;
}
</style>

<div class="scroll_wrapper">
  <div class="scroll">
     {% for post in site.posts %}
        {% include post-card.html %}
     {% endfor %}
  </div>
</div>
