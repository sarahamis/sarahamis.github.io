---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
youtubeId: a6enBhsbrX4?si=H2ebPhr6FQ_0M1oL
---

<div class="container">
  <div class="left-column">
    <h2> A one-minute film about my research </h2>
    <p> This film introduces my mathematical oncology research.
    It was filmed at Tampere University, where I was a Wenner-Gren Fellow and a Tampere Institute for Advanced Study Fellow (2021-2023).
     </p>
  </div>

  <div class="right-column">
    <h2> </h2>
    <p> {% include youtubePlayer.html id=page.youtubeId %} </p>
  </div>
</div>

<style>
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center; /* Center vertically */
  }

  .left-column {
    flex: 1;
    margin-right: 10px; /* Adjust the spacing between columns as needed */
  }

  .right-column {
    flex: 1;
    margin-left: 10px; /* Adjust the spacing between columns as needed */
  }

  .content {
    display: flex;
    flex-direction: column;
    align-items: center; /* Center vertically */
    text-align: center; /* Center horizontally */
  }
</style>
