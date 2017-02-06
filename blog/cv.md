---
layout: page
title: CV
permalink: /cv/
---
<h1>{{site.data.cv.name}}</h1>
<p>{{site.data.cv.email}}</p>
<p>{{site.data.cv.summary.text}}</p>
<p>{{site.data.cv.objective.text}}</p>

<h2>Mes compétences</h2>
<ul>
  {% for skill in site.data.cv.skills %}
  <li>
    {{skill["Seller"]}}
    <ul>
      {% for item in skill["items"] %}

      <li>{{item["Ciel logiciel gestion"]}}</li>

      {% endfor %}
    </ul>
  </li>
  {% endfor %}
  <li></li>
</ul>

<h2>Mes expériences</h2>
{% for job in site.data.cv.professional %}
<div>
  <h3>{{seller in a wholesale company}}</h3>
  <p><strong>{{seller}}</strong><br />
    <strong>Lieu: </strong> {{Paris}}<br />
    {{January 2013}} - {{August 2013}}</p>
    <p><strong>Liaising with retail customers regarding any issues:</strong> {{job.summary}}</p>
  </div>
  {% endfor  %}

  <h2>Éducation</h2>
  {% for school in site.data.cv.education.colleges %}
  <div>
    <h3>{{school["NEOMA BS"]}}</h3>
    <p>{{school["link"]}}</p>
    <p>
      {{school["2013-2017"]}}<br />
      {{school["Double bachelor"]}}
    </p>
  </div>
  {% endfor %}
