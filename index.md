---
layout: page
title: Everquest Guide
tagline: mainly for Returnees and Newbies
---
{% include JB/setup %}

Welcome to Everquest Guides.  I will be adding new guides over time, aiming to cover the low and mid level experience for new and returning players.  The look of the site is also subject to change!

<h2>New Players</h2>

- [The Mines of Gloomingdeep](guides/mines-of-gloomingdeep)

<h2>Everquest Anniversary</h2> 
(16 March - 16 April every year)

- [Anniversary Quests](guides/anniversary-quests)
- [Fabled Mobs](guides/fabled-mobs)
- [Fabled Pet Weapons](guides/fabled-pet-weapons)

<h2>Forthcoming</h2>

- Crescent Reach
- Blightfire Moors
- Hot Zones
- Frostfell Quests
- Halloween Quests
- The Kunark Express
- The Luclin Express
- The Serpent's Spine Express
- The Hero's Journey


<h2>News:</h2>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="http://www.paullynch.org/eqguide{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
