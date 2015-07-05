---
layout: page
title: Photography
#image:
#   feature: colpat/CP2011-04-10_P24053_ST.jpg
#  thumb: colpat/CP2011-04-10_P24053_TN.jpg
---


{% for gallery in site.data.galleries %}

   -  [<img class="example-image" src="{{ gallery.imagefolder }}/{{ gallery.feature }}" width="50em" align="leftt" alt=""/> <font size="+3">{{ gallery.description }}</font>]({{ site.url }}/gallery/{{ gallery.id }})

{% endfor %}



