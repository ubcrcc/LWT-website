---
---

# Welcome!

UBC Red Cross is a student-run non-profit club that upholds the seven values of the Canadian Red Cross: humanity, voluntary service, impartiality, neutrality, independence, unity, and universality. Through our five committees, we run volunteer events, host training sessions, organize speaker series, raise money, and so much more. We’re committed to improving the UBC and Vancouver community, as well as supporting global causes. 



{% include section.html %}

{%
  include button.html
  type="link"
  link="signup"
  icon="fa-solid fa-link"
  text="Join Us"
  tooltip="Explore ways to get involved"
  flip=true
%}

## Highlights

{% capture text %}

Want to help make a difference? Find an event that works for you, and come help us support great causes around Vancouver. Everyone welcome!

{%
  include button.html
  link="events"
  text="Upcoming events"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/spoonful.jpg"
  link="events"
  title="Events"
  text=text
%}

{% capture text %}

Learn more about our club, including why we do what we do. Find out more about our five committees, Fundraising, Outreach and Awareness, Humanitarian Movement, Training, and Marketing.

{%
  include button.html
  link="team"
  text="Learn more about us"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/big_logo.png"
  link="about"
  title="About"
  flip=true
  text=text
%}

{% capture text %}

Learn more about some of the great people who make up the UBC Red Cross Club. Our team includes students from all backgrounds and years!

{%
  include button.html
  link="people"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/gm_people.jpg"
  link="people"
  title="People"
  style="bare"
  text=text
%}



