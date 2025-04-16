---
title: "Grad Cohort 2025"
layout: post
date: 2025-04-09 16:11:00-0400
inline: true
---
Grad Cohort CRA – Fun & Insightful!
<div class="row">
  <div class="col-sm-12 mt-3 photo-stack-wrapper">
    <div class="photo-stack">
      {% include figure.html path="assets/img/GC-1.jpg" width="300" height="300" title="Grad Cohort 2025" class="stacked-img img-fluid rounded z-depth-1 img1" %}
      {% include figure.html path="assets/img/GC-2.JPG" width="300" height="300" title="Grad Cohort 2025" class="stacked-img img-fluid rounded z-depth-1 img2" %}
    </div>
  </div>
</div>

<style>
.photo-stack-wrapper {
  height: 350px; /* adjust based on how tall the stacked images are */
  position: relative;
}

.photo-stack {
  position: absolute;
  width: max-content;
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
