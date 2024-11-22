---
layout: post
title: "Departure: Updates List"
tags: ss14_departure
---

These posts contain some updates to the [Departure]({% post_url 2024-11-10-departure %}) post, including addressing some things I've been asked about or seen. Unlike the previous post, these are not from all of the former headmins, they are just from me.

This page will continue to be updated when a new post is added. Check the bottom of the page for ways to get notified when new posts are made.

### Post List

{% assign sorted_posts = site.tags.ss14_departure_updates | sort: "date" %}
{% for post in site.tags.ss14_departure_updates %}
- {{ post.date | date_to_string }} -- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
