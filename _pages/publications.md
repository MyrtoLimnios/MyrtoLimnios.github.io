---
layout: archive
permalink: /publications/
author_profile: true

---


<h3>Preprints</h3>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'preprint' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %}
  
<h3>Journals</h3>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'journal' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %}



<h3>Conferences</h3>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'conference' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %}


  <h3>Ph.D. thesis and Book Chapter</h3>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'phd' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %}
