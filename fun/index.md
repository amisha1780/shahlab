---
title: Fun
nav:
  order: 5
  tooltip: Fun Activities In and Outside the Lab
---

# {% include icon.html icon="fa-regular fa-face-laugh" %}Fun!

Memories from our group. It has been such a joy to share science, hobbies, and food together!!! 

<div style="column-count: 3; column-gap: 10px; width: 100%; padding: 0; box-sizing: border-box;">
  <img src="/shahlab/images/fun_photo1.jpg" style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo2.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo3.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo4.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo5.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo6.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo7.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo8.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo9.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo10.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo11.jpg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
  <img src="/shahlab/images/fun_photo12.jpeg"  style="width: 100%; display: block; margin-bottom: 10px; border-radius: 8px;">
</div>

{% comment}

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
