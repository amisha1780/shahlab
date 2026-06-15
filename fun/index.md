---
title: Fun
nav:
  order: 5
  tooltip: Fun Activities In and Outside the Lab
---

# {% include icon.html icon="fa-sharp fa-solid fa-party-horn" %} Fun

<div style="column-count: 3; column-gap: 10px; width: 100%; padding: 0; box-sizing: border-box;">
  <img src="images/photo1.jpg" alt="Lab Fun 1" style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="images/photo2.jpg" alt="Lab Fun 2" style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="images/photo3.jpg" alt="Lab Fun 3" style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="images/photo4.jpg" alt="Lab Fun 4" style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="images/photo5.jpg" alt="Lab Fun 5" style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="images/photo6.jpg" alt="Lab Fun 6" style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
</div>



{% comment}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
{% endcomment %}
