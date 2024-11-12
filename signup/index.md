---
title: Sign Up
nav:
  order: 2
  tooltip: Get involved with the club
---

{% include section.html %}

# {% include icon.html icon="fa-solid fa-arrow-right-to-bracket" %}Join As A Member

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="none"
  text="Become A Member"
  link="https://docs.google.com/forms/d/e/1FAIpQLSdvPpvsSEvzkeqfnKPS8oLMpiUR9hpS8MxnctOJhgYTkORqAw/viewform?usp=sharing"
%}

## Position Postings

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
