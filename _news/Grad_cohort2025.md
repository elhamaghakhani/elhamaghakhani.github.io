---
title: "Grad Cohort 2025"
layout: post
date: 2025-04-09 16:11:00-0400
inline: true
---
Grad Cohort CRA – Fun & Insightful!

<div class="row justify-content-center">
  <div class="photo-stack-wrapper">
    <div class="photo-stack">
      {% include figure.html path="assets/img/GC-1.jpg" title="Photo 1" class="stacked-img img1" %}
      {% include figure.html path="assets/img/GC-2.JPG" title="Photo 2" class="stacked-img img2" %}
    </div>
  </div>
</div>

<style>
.photo-stack-wrapper {
  display: block;
  max-width: 300px;
  margin: 0 auto;
  height: 350px;
  position: relative;
}

.photo-stack {
  position: relative;
  width: 100%;
  height: 100%;
}

.stacked-img img {
  width: 100%;
  height: auto;
  position: absolute;
  transition: transform 0.3s ease;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.img1 img {
  transform: rotate(-5deg);
  z-index: 1;
}

.img2 img {
  transform: rotate(8deg);
  left: 30px;
  top: 20px;
  z-index: 2;
}
</style>
