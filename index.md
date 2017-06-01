---
layout: svenska
title: Svenska Discord
subtitle: Tips, hint, frequently asked questions, course material...
show_downloads: false
---

## Welcome

Welcome to the [Svenska-Discord](https://discord.gg/FUMTtWJ) website!

If you'd like to contribute, create a Github account then send **sustained** a DM with your username or email address. 

## Latest Blog Posts

<ul>
{% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>

        {{ post.excerpt }}
    </li>
{% endfor %}
</ul>