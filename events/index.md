---
title: Events
nav:
  order: 1
  tooltip: Upcoming and past events
---

# {% include icon.html icon="fa-solid fa-calendar-days" %}Events

Check out some of our upcoming opportunities as well as some of our most recent Red Cross events! Click on events for more information, as well as dates, locations, and sign up. Not a member? No worries! Anyone can attend most of our events, but members might get discounts on event costs, and will get priority registration.

{% include section.html %}

{% include search-box.html %}
{% include search-info.html %}

{% include section.html %}

## Upcoming Events

{% include list.html component="card" data="projects" filter="group == 'upcoming'" %}

{% include section.html %}

## Past Events

{% include list.html component="card" data="projects" filter="!group" style="small" %}

