---
layout: page
title: Playlist
permalink: /playlist/
---
Here is my youtube videos playlist. Have fun !

<ul>
  {% for playlist in site.data.playlist %}
  <li>
      <p>{{ playlist.name }}</p>
      <iframe width="560" height="315" src="{{playlist.source}}" frameborder="0" allowfullscreen></iframe>
  </li>
  {% endfor %}
</ul>
