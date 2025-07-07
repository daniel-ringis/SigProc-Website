---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are Electrical and Computer Engineering Researchers, from the University of the West Indies. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html %}

# PhD Researchers

{% include list.html data="members" component="portrait" filter="role == 'phd' and description != 'template'" %}

# Masters Students

{% include list.html data="members" component="portrait" filter="role == 'postgrad' and description != 'template'" %}

# Undergraduate Students

{% include list.html data="members" component="portrait" filter="role == 'undergrad' and description != 'template' and description != 'alumni'"%}

# Alumni

{% include list.html data="members" component="portrait" filter="description == 'alumni'" %}


{% include section.html background="images/background.jpg" dark=true %}

We have many more alumni over the years, we will continue to add!


