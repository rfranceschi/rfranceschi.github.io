---
author_profile: true  # Or false if you don't want the sidebar
layout: single
title: "Riccardo Franceschi"
header:
  overlay_image: /assets/images/JWST_PPD.jpg
  overlay_filter: 0.5
  caption: "Image credit: NASA / JPL-Caltech"
excerpt: >
  Data Scientist | Machine Learning & Bayesian Modeling<br/><br/>
  Extracting actionable insights from complex, noisy datasets
---

<!-- Full bio section (text only, centered or wide) -->
<div class="feature__wrapper">
  <div class="feature__item--left">
    <div class="archive__item-body">
      <p>I am a data scientist with a PhD in astrophysics from the Max Planck Institute for Astronomy (Germany), currently a postdoctoral researcher at the Paris Observatory (France). I hold MSc and BSc degrees in Astrophysics and Physics from the University of Pisa (Italy). Specializing in extracting insights from complex, noisy, high-dimensional datasets, I am proficient in Python (pandas, NumPy, scikit-learn, PyTorch) and SQL.</p>

      <p>I have built end-to-end data pipelines, developed machine learning models with scikit-learn, applied nested sampling Bayesian methods for parameter estimation and uncertainty quantification, and designed Monte Carlo simulation tools (e.g., for protoplanetary disk evolution and cosmic ray propagation). Experienced in statistical analysis of incomplete data and reproducible workflows with Docker, I have authored peer-reviewed publications and presented at international conferences—honing strong communication skills for translating technical findings to diverse audiences.</p>

      <p>Eager to apply this expertise to impactful industry challenges in machine learning, AI, Bayesian modeling, and data-driven innovation—particularly in climate science, environmental modeling, renewable energy, or risk assessment, though open to diverse domains where rigorous data analysis drives real-world outcomes.</p>

      <!-- Optional buttons -->
      <a href="/projects/" class="btn btn--primary">View Projects</a>
      <a href="/assets/files/cv.pdf" class="btn btn--success">Download CV</a>
    </div>
  </div>
</div>

<!-- Portrait on the right (upload your photo to /assets/images/me.jpg or similar) -->
{% include feature_row id="portrait" type="right" %}

{% capture portrait_fig %}
<img src="/assets/images/me.png" alt="Riccardo Franceschi" class="img-circle" style="max-width: 300px;">
{% endcapture %}

{% assign feature = site.data.features | where: "id", "portrait" | first %}

{% include feature_row content=portrait_fig image_path="/assets/images/me.png" image_circle=true image_alt="Riccardo Franceschi" %}
