---
title: About
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-solid fa-earth-americas" %}About UBC Red Cross

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

# Outreach and Awareness

<!--- Check out this page from the docs for some of the images settings:
https://greene-lab.gitbook.io/lab-website-template-docs/basics/components/figure

Also, feel free to have more or fewer than two pictures per committee, either copy the format below to add more or delete everything but the image block below to remove pictures. -->

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  width="100%"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  width="100%"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
