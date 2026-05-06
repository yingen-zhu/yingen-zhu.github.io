---
layout: default
title: Gallery
permalink: /gallery/
---

# Visual Records 

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 40px;
}
.gallery-item img {
  width: 100%;
  height: auto;
  display: block;
  max-width: 100%;
}
@media (max-width: 900px) {
  .gallery-grid {
    grid-template-columns: 1fr;
  }
}
</style>

---

<div class="gallery-grid">
  <section class="gallery-item">
    <h3>NUS, Singapore</h3>
    <img src="/assets/images/nus.jpg" alt="nus">
  </section>

  <section class="gallery-item">
    <h3>SUSTech, China</h3>
    <img src="/assets/images/sustech.JPG" alt="sustech">
  </section>
</div>


