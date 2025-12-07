---
layout: default
title: "Home"
permalink: /
---

<section class="hero">
  <div class="hero-text">
    <h1>Hi, I'm <span>Murad Rzayev</span></h1>
    <p class="lead">
      I’m an IT student from Baku, interested in cybersecurity and backend development.
    </p>

    <div class="hero-tags">
      <span class="tag">IT Student</span>
      <span class="tag">Cybersecurity</span>
      <span class="tag">Backend Dev</span>
    </div>

    <div class="hero-actions">
      <a href="{{ '/about/' | relative_url }}" class="btn btn-primary">More about me</a>
      <a href="{{ '/projects/' | relative_url }}" class="btn btn-outline">My projects</a>
    </div>

  </div>

  <div class="hero-photo-wrapper">
    <div class="hero-photo">
      <img src="{{ '/assets/profile.jpg' | relative_url }}" alt="Photo of Murad Rzayev">
    </div>
  </div>
</section>
