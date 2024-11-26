---
title: Sign Up
nav:
  order: 2
  tooltip: Get involved with the club
---

{% include section.html %}

# {% include icon.html icon="fa-solid fa-arrow-right-to-bracket" %}Join As A Member

Joining UBC Red Cross Club as a member is a great way to get involved and start making a difference in the club. As a member you can:

<ul>
  <li>Attend our general meetings and help make decisions like our initiative of the year</li>
  <li>Get priority registration for events through our newsletter and pay less to attend some events</li>
  <li>Join a committee and volunteer to help organize and run events</li>
</ul>

{%
  include button.html
  type="none"
  text="Become A Member"
  link="https://docs.google.com/forms/d/e/1FAIpQLSdvPpvsSEvzkeqfnKPS8oLMpiUR9hpS8MxnctOJhgYTkORqAw/viewform?usp=sharing"
%}

## Position Postings

Check the board below for leadership positions available in UBCRCC. Becoming an officer, director, or even executive is a great way to get more involved! Although you can keep an eye out for positions any time, expect most to appear around April and September.

{% include section.html %}

{% include search-box.html %}
{% include tags.html tags=site.tags %}
{% include search-info.html %}

{% assign num_posts = site.posts | size %}

{% if num_posts == 0 %}
  <p style="text-align: center; font-size: 18px;">No positions available</p>
{% else %}
  {% include list.html data="posts" component="post-excerpt" %}
{% endif %}
