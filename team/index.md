---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are Electrical and Computer Engineering Researchers, from the University of the West Indies. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role = 'phd'" %}

{% include section.html background="images/background.jpg" dark=true %}

The best way to contact us is by email. We do not have an email for the collective, so it's best to reach out to Daniel if you arent sure who to reach out to.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
