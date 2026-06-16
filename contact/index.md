---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

The Shah lab is jointly housed within the Lyles School of Civil and Construction Engineering and the Department of Sustainability Engineering and Environmental Engineering. The physical lab is located on the 3rd floor of Hampton Hall at Purdue University's West Lafayette campus. <br>
<br>
Please feel free to reach out to PI Shah if you are interested in learning more about our work or are interested in joing our group.

{%
  include button.html
  type="email"
  text="adshah@purdue.edu"
  link="adshah@purdue.edu"
%}
{%
  include button.html
  type="phone"
  text="(765) 496-2470"
  link="+1-765-496-2470"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/8RGYaBLKojvXGwMKA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="/shahlab/contact/purdue_cce.jpeg"
  
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="/shahlab/contact/purdue_see.jpeg"
 
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="/shahlab/contact/purdue_try2.jpg"

%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3 = col3 %}

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
