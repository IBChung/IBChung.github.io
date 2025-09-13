---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<h1>Publications</h1>

{% assign pubs = site.publications | sort: 'year' | reverse %}

{% assign last_year = "" %}
{% for pub in pubs %}
  {% assign current_year = pub.year %}
  
  {% if current_year != last_year %}
    <h2>{{ current_year }}</h2>
    <hr>
    {% assign last_year = current_year %}
  {% endif %}

  <div class="pub-entry" style="margin-bottom: 1.2em; text-align: justify;">
    <p>
      {% if pub.authors %}<strong>{{ pub.authors }}</strong>. {% endif %}
      {% if pub.title %} 
        <a href="{{ pub.link | default: '#' }}">{{ pub.title }}</a>. 
      {% endif %}
      {% if pub.journal %}<em>{{ pub.journal }}</em>. {% endif %}
      {% if pub.extra %} {{ pub.extra }}. {% endif %}
    </p>
  </div>
{% endfor %}
