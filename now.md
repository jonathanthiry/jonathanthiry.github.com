---
layout: page
permalink: /now
date: 2017-04-02
---

I am working at Lund's University on the [Swedish Infrastructure for Ecosystem Science project](http://www.fieldsites.se/en-GB) and the [ICOS Carbon Portal](https://www.icos-cp.eu/) since September 2017 where I'm helping researchers to store and distribute data on the environment.
Samantha and I got a house in the Swedish countryside in August. I enjoy spending a lot of time on my work and the house right now, but I also take the chance to spend time on:

- Working on the next version of [Wonder](https://itunes.apple.com/us/app/wonder-reader-for-wikipedia/id1050888989?mt=8&at=1010lo2M) -- 1.4 added a swiping gesture to close tabs, restoration of the scrolling position on launch, and custom peek and pop preview -- Progress we'll be slower now that I got a full time job
- Reading [Natural Born Heroes](https://www.goodreads.com/book/show/22889750-natural-born-heroes) and [Voyage au Centre de la Terre](https://fr.wikipedia.org/wiki/Voyage_au_centre_de_la_Terre)
- Working out -- my daily training is based on calisthenics, at home and at the gym
- Meditating a few minutes every day, preferably in the morning
- Playing with Rust and PostgreSQL

Last updated on the {% assign d = page.date | date: "%-d" %}
{% case d %}{% when '1' or '21' or '31' %}{{ d }}st{% when '2' or '22' %}{{ d }}nd{% when '3' or '23' %}{{ d }}rd{% else %}{{ d }}th{% endcase %}
of {{ page.date | date: "%B" }}
{{ page.date | date: "%Y" }}

*Inspired by [Derek Sivers](https://sivers.org/nowff)*
