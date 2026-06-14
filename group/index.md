---
title: Group
nav:
  order: 4
  tooltip: About our group members
---

# {% include icon.html icon="fa-solid fa-users" %}Group

{% include section.html %}

## PI and Current Group Members

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" filter = "group =='PI and Current Group Members'"  %}

{% include section.html %}

## Past Group Members

{% include list.html data="members" component="portrait" filter = "group =='Past Group Members'" %}


{% comment %}

{% include section.html background="images/background.svg" dark=false %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
{% endcomment %}
