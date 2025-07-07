---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We do not have a contact for the collective group, however emailling Daniel is best. 

{%
  include button.html
  type="email"
  text="daniel.ringis@uwi.edu"
  link="mailto:daniel.ringis@uwi.edu"
%}
{%
  include button.html
  type="phone"
  text="(868) 662-2002 ext 8XXXX"
  link="(868) 662-2002"
%}
{%
  include button.html
  type="address"
  tooltip="Visit us at The University of the West Indies, St. Augustine, Trinidad and Tobago"
  link="https://maps.app.goo.gl/zzPZzuki2zSo6bwr9"
%}

{% include section.html %}

# {% capture col1 %}

# {%
#   include figure.html
#   image="images/photo.jpg"
#   caption="Lorem ipsum"
# %}

# {% endcapture %}

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
