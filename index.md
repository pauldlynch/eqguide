---
layout: page
title: Everquest Guide
tagline: mainly for Returnees and Newbies
---
{% include JB/setup %}

Welcome to Everquest Guides.  I will be adding new guides over time, aiming to cover the low and mid level experience for new and returning players.  The look of the site is also subject to change!

New Players
-----------

- [The Mines of Gloomingdeep](guides/mines-of-gloomingdeep)
- [Plane of Knowledge Quests](guides/plane-of-knowledge-quests)
- [Crescent Reach](guides/crescent-reach)

Everquest Anniversary
---------------------
(16 March - 16 April every year)

- [Anniversary Quests](guides/anniversary-quests)
- [Fabled Mobs](guides/fabled-mobs)
- [Fabled Pet Weapons](guides/fabled-pet-weapons)

General Information
-------------------

- [Hot Zones](guides/hot-zones)

The Hero's Journey
------------------

- [The Hero's Journey](guides/heros-journey)
- [Serpent Seeker's Charm of Lore](guides/charm-of-lore)
- [Wanderlust Guild Loadstone](guides/wanderlust-guild-loadstone)

<h2>Forthcoming</h2>

- Blightfire Moors
- Frostfell Quests
- Halloween Quests
- The Kunark Express
- The Luclin Express
- The Serpent's Spine Express


<h2>News:</h2>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="http://www.paullynch.org/eqguide{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
