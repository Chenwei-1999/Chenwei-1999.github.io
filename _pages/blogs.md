---
layout: archive
title: "Blogs"
permalink: /blogs/
author_profile: true
---

<style>
  .blog-index {
    margin-top: 0.75rem;
  }

  .blog-intro {
    max-width: 42rem;
    margin: 0 0 1.75rem;
    color: #4b5563;
    line-height: 1.65;
  }

  .blog-section {
    margin-top: 2rem;
  }

  .blog-section__label {
    margin: 0 0 0.75rem;
    color: #6b7280;
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0;
    text-transform: uppercase;
  }

  .blog-list {
    display: grid;
    gap: 0.9rem;
  }

  .blog-card {
    border: 1px solid #e5e7eb;
    border-left: 4px solid #2f5f72;
    border-radius: 6px;
    padding: 1rem 1.1rem;
    background: #fff;
    box-shadow: 0 8px 20px rgba(31, 41, 55, 0.05);
  }

  .blog-card--project {
    border-left-color: #85613a;
    background: linear-gradient(90deg, rgba(133, 97, 58, 0.06), rgba(255, 255, 255, 0) 58%), #fff;
  }

  .blog-card__title {
    margin: 0;
    font-size: 1.05rem;
    line-height: 1.35;
  }

  .blog-card__title a {
    color: #111827;
    text-decoration: none;
  }

  .blog-card__meta {
    margin: 0.25rem 0 0.55rem;
    color: #6b7280;
    font-size: 0.78rem;
    font-weight: 600;
  }

  .blog-card__summary {
    margin: 0 0 0.75rem;
    color: #374151;
    line-height: 1.55;
  }

  .blog-card__links a {
    display: inline-block;
    margin-right: 0.8rem;
    font-size: 0.82rem;
    font-weight: 700;
    text-decoration: none;
    border-bottom: 1px solid rgba(47, 95, 114, 0.35);
  }

  .blog-card__links a:hover {
    border-bottom-color: currentColor;
  }

  @media (max-width: 600px) {
    .blog-card {
      padding: 0.9rem;
    }
  }
</style>

<div class="blog-index">
  <p class="blog-intro">Talk decks, technical notes, and small projects that are useful enough to keep close at hand.</p>

  <section class="blog-section" aria-labelledby="talks-and-slides">
    <h2 id="talks-and-slides" class="blog-section__label">Talks and Slides</h2>
    <div class="blog-list">
      <article class="blog-card">
        <h3 class="blog-card__title"><a href="/blogs/ddpm/">Denoising Diffusion Probabilistic Models</a></h3>
        <p class="blog-card__meta">Slides</p>
        <p class="blog-card__summary">A compact deck introducing the original DDPM framework and its probabilistic modeling view.</p>
        <p class="blog-card__links">
          <a href="/blogs/ddpm/">Details</a>
          <a href="/files/slides/DDPM_V1.pdf">PDF</a>
          <a href="/files/slides/DDPM_V1.pptx">PowerPoint</a>
        </p>
      </article>

      <article class="blog-card">
        <h3 class="blog-card__title"><a href="/blogs/distributed-computing/">Distributed Computing</a></h3>
        <p class="blog-card__meta">Slides</p>
        <p class="blog-card__summary">A teaching-oriented slide deck on distributed computing concepts, systems, and design trade-offs.</p>
        <p class="blog-card__links">
          <a href="/blogs/distributed-computing/">Details</a>
          <a href="/files/slides/Distributed_Computing.pdf">PDF</a>
          <a href="/files/slides/Distributed_Computing.pptx">PowerPoint</a>
        </p>
      </article>
    </div>
  </section>

  <section class="blog-section" aria-labelledby="projects">
    <h2 id="projects" class="blog-section__label">Projects</h2>
    <div class="blog-list">
      <article class="blog-card blog-card--project">
        <h3 class="blog-card__title"><a href="/blogs/agent-self-improvement/">Agent Self-Improvement</a></h3>
        <p class="blog-card__meta">Open-source agent skill</p>
        <p class="blog-card__summary">A portable skill for turning real agent conversation history into evidence-backed behavior updates.</p>
        <p class="blog-card__links">
          <a href="/blogs/agent-self-improvement/">Details</a>
          <a href="https://github.com/Chenwei-1999/agent-self-improvement">GitHub</a>
        </p>
      </article>
    </div>
  </section>
</div>
