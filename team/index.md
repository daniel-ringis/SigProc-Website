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

{% include list.html data="members" component="portrait" filter="role == 'phd'","description != 'template'" %}

# Masters Students

{% include list.html data="members" component="portrait" filter="role == 'postgrad'","description != 'template'" %}

# Undergraduate Students

{% include list.html data="members" component="list" filter="role == 'undergrad'","description != 'template'"%}

# Alumni

{% include list.html data="members" component="list" filter="description == 'alumni'" %}


{% include section.html background="images/background.jpg" dark=true %}

The best way to contact us is by email. We do not have an email for the collective, so it's best to reach out to Daniel if you arent sure who to reach out to.


