---
title: "Grad Cohort 2025"
layout: post
date: 2025-04-09 16:11:00-0400
inline: true
---
Grad Cohort CRA – Fun & Insightful!
<div class="row">
  <div class="photo-stack-wrapper">
    <div class="photo-stack">
      {% include figure.html path="assets/img/GC-1.jpg" width="400" height="400" title="Photo 1" class="stacked-img img1" %}
      {% include figure.html path="assets/img/GC-2.JPG" width="400" height="400" title="Photo 2" class="stacked-img img2" %}
    </div>
  </div>
</div>

<style>

.photo-stack-wrapper {
  display: inline-block;
  height: 350px;
  width: 100%;
}

.photo-stack {
  position: relative;
  width: max-content;
  margin: auto;
  height: 100%; /* Add this line */
}

.stacked-img {
  position: absolute;
  transition: transform 0.3s ease;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

.img1 {
  transform: rotate(-5deg);
  z-index: 1;
}

.img2 {
  transform: rotate(8deg);
  left: 30px;
  top: 20px;
  z-index: 2;
}

</style>
