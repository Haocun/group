---
title: "Gallery"
permalink: /gallery/
layout: splash
author_profile: false


feature_row:
   - image_path: /assets/images/vienna_lab1.jpg
     #alt: "placeholder image 1"
     title: "Quantum information"
     excerpt: "This is some sample content that goes here with **Markdown** formatting."
   - image_path: /assets/images/gw_feat.jpg
     image_caption: "Image 1"
     alt: "placeholder image 2"
     title: "Fundamental physics"
     excerpt: "This is some sample content that goes here with **Markdown** formatting."
   - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
     title: "Placeholder 3"
     excerpt: "This is some sample content that goes here with **Markdown** formatting."

---
{% include feature_row %}

<style>
.gallery-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 24px;
  justify-content: center;
}
.gallery-grid figure {
  width: 300px;
  margin: 0;
  text-align: center;
}
.gallery-grid img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
}
.gallery-grid figcaption {
  font-size: 0.9rem;
  margin-top: 8px;
  color: #555;
}
</style>

<div class="gallery-grid">

<p class="caption-above">
  Photo from the Quantum Information Science and Quantum Computation Lab at the University of Vienna
</p>

  <figure>
    <img src="/assets/images/vienna_lab1.jpg">
    <figcaption>Photon source</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/vienna_lab3.jpg">
  </figure>

  <figure>
    <img src="/assets/images/vienna_lab4.jpg">
    <figcaption>Quantum optics experiment at University of Vienna</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/mit_sqz1.jpg">
    <figcaption>Squeezer</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/vienna3.jpg" >
    <figcaption>Laser system in Vienna quantum lab</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/ligo3.jpg">
    <figcaption>Electronics rack for LIGO interferometer controls</figcaption>
  </figure>

</div>