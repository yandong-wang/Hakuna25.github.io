---
permalink: /Misc
title: "Misc"
excerpt: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🏊🏄🎶📷 Misc
- **Wave Surfing**: Novice
- **Swimming**: Skilled in four strokes 
- **Ukulele and flute**: novice
- **Piano**: Level 10 in amateur piano
- **Photography**

# Glimpse Through my Lens
<!-- <div style="display: flex; align-items: center;  " >
   <div style="position: relative; width: 50%; margin-right: 10px;">
    <img src="/images/sheep.png" style="width: 100%; border-radius: 8px; display: block;">
    <div style="
      position: absolute;
      bottom: 10px;
      left: 10px;
      color: white;
      background: rgba(0, 0, 0, 0.6);
      padding: 4px 8px;
      font-size: 14px;
      border-radius: 4px;
    ">
      Filmed in Altay (Jun 2024)
    </div>
  </div>
  <div style="font-size: 16px; padding-right:10px">
    <p>✔ Got stuck in a massive herd of sheep and cattle crossing the road</p>
    <p>✔ A boundless sea of verdant grass</p>
  </div>
</div> -->
<div class="container">
 <div class="image-section">
    <img src="/images/sheep.png" alt="sheep">
    <div class="caption">Filmed in Altay (Jun 2024)</div>
  </div>
  <div class="text-section">
    <p>✔ Got stuck in a massive herd of sheep and cattle crossing the road</p>
    <p>✔ A boundless sea of verdant grass</p>
  </div>

</div>

***

<div class="container">
  <div class="text-section">
    <p>✔ Monument Valley through the window of a gift shop</p>
    <p>✔ Highway 163, the endless road from Forrest Gump</p>
    <p>✔ A ruby-hued light pillar rising beneath the sunset </p>
  </div>
  <div class="image-section">
    <img src="/images/monument.png" alt="Monument Valley">
    <div class="caption">Filmed in Page (Mar 2025)</div>
  </div>
</div>

***
<!-- <div style="display: flex; align-items: center;  " >
  <div style="font-size: 16px; padding-right:5px">
    <p>✔ Monument Valley through the window of a gift shop</p>
    <p>✔ Highway 163, the endless road from Forrest Gump</p>
    <p>✔ A ruby-hued light pillar rising beneath the sunset </p>
  </div>
   <div style="position: relative; width: 50%; margin-left: 105px;">
    <img src="/images/monument.png" style="width: 100%; border-radius: 8px; display: block;">
    <div style="
      position: absolute;
      bottom: 10px;
      left: 25px;
      color: white;
      background: rgba(0, 0, 0, 0.6);
      padding: 4px 8px;
      font-size: 14px;
      border-radius: 4px;
    ">
      Filmed in Page (Mar 2025)
    </div>
  </div>
  
</div> -->

<style>
  .container {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }
  .text-section {
    font-size: 16px;
    padding-right: 5px;
    flex: 1;
    min-width: 250px;
  }

  .image-section {
    position: relative;
    width: 50%;
    min-width: 250px;
  }

  .image-section img {
    width: 100%;
    border-radius: 8px;
    display: block;
  }

  .caption {
    position: absolute;
    bottom: 10px;
    left: 25px;
    color: white;
    background: rgba(0, 0, 0, 0.6);
    padding: 4px 8px;
    font-size: 14px;
    border-radius: 4px;
  }

  /* Responsive for smaller screens */
  @media (max-width: 768px) {
    .container {
      flex-direction: column;
      align-items: stretch;
    }

    .image-section {
      width: 100%;
      margin-left: 0;
    }

    .text-section {
      padding-right: 0;
      text-align: center;
    }

    .caption {
      left: 10px;
      font-size: 12px;
    }
  }
</style>