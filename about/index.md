---
title: About
nav:
  order: 6
  tooltip: Email, address, and location
---

# About UBC Red Cross

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

# Outreach and Awareness

{% capture col1 %}

<!-- Want more or fewer pictures? Add another column with the same syntax as this code, or use just the block below. -->
{%
  include figure.html
  image="images/photo.jpg" <!-- Remember, you can change this path to be your own picture, stored in the "images" folder. -->
  width="100%" <!-- Change this to change the size of the pictures, especially if you use a different number of pics. -->
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

<!-- Copy the above section for the rest of the committees. -->
