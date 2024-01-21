---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
youtubeId: a6enBhsbrX4?si=H2ebPhr6FQ_0M1oL
---






<div class="container">
  <div class="left-column">
    <h2>Left Column</h2>
    <p> ## A one-minute film about my research </p>
  </div>

  <div class="right-column">
    <h2>Right Column</h2>
    <p> {% include youtubePlayer.html id=page.youtubeId %} </p>
  </div>
</div>

<style>
  .container {
    display: flex;
    justify-content: space-between;
  }

  .left-column {
    flex: 1;
    margin-right: 10px; /* Adjust the spacing between columns as needed */
  }

  .right-column {
    flex: 1;
    margin-left: 10px; /* Adjust the spacing between columns as needed */
  }
</style>

