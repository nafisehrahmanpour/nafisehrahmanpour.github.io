---
layout: page
permalink: /in-memoriam/
title: "In Loving Memory"
description: ""
nav: false
nav_order: 99
giscus_comments: false
sitemap: false
robots: noindex
---

<meta name="robots" content="noindex, nofollow">


<style>
.memoriam {
  max-width: 640px;
  margin: 0 auto;
  text-align: center;
}
.memoriam .memoriam-photo {
  max-width: 320px;
  margin: 1rem auto 1.5rem;
}
.memoriam .memoriam-photo img {
  border-radius: 6px;
}
.memoriam .memoriam-name {
  font-size: 1.6rem;
  margin-bottom: 0.25rem;
}
.memoriam .memoriam-dates {
  opacity: 0.7;
  margin-bottom: 0.5rem;
}
.memoriam .memoriam-role {
  opacity: 0.6;
  font-size: 0.95rem;
  margin-bottom: 2rem;
}
.memoriam .memoriam-tribute {
  text-align: left;
  line-height: 1.8;
  font-size: 1.05rem;
}
.memoriam .memoriam-tribute p {
  margin-bottom: 1.25rem;
}
.memoriam blockquote {
  font-style: italic;
  opacity: 0.85;
  margin: 2rem auto;
  max-width: 480px;
}
.memoriam .memoriam-section-title {
  text-align: left;
  font-size: 1.1rem;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  opacity: 0.55;
  margin: 3rem 0 1.25rem;
  border-top: 1px solid rgba(0, 0, 0, 0.08);
  padding-top: 2rem;
}
.memoriam .memoriam-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
  gap: 12px;
}
.memoriam .memoriam-gallery figure {
  margin: 0;
  aspect-ratio: 1 / 1;
  overflow: hidden;
  border-radius: 6px;
}
.memoriam .memoriam-gallery img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.memoriam .memoriam-placeholder-note {
  text-align: left;
  opacity: 0.5;
  font-style: italic;
  font-size: 0.95rem;
}
.memoriam .memoriam-stories {
  text-align: left;
  line-height: 1.8;
  font-size: 1.05rem;
}
.memoriam .memoriam-story {
  margin-bottom: 1.75rem;
}
.memoriam .memoriam-story-title {
  font-weight: 600;
  margin-bottom: 0.35rem;
}
</style>

<div class="memoriam">

  <div class="memoriam-photo">
    <!-- Replace with a real photo, e.g. assets/img/dad.jpg -->
    {% include figure.liquid path="assets/img/dad.jpg" class="img-fluid" alt="Photo of my father" %}
  </div>

  <div class="memoriam-name">Kazem</div>
  <div class="memoriam-dates">78 years</div>
  <div class="memoriam-role">Engineer &middot; father of four</div>

  <div class="memoriam-tribute">
    <p>Kazem was an engineer — steady, capable, and someone people could count on. For most of his life he was strong and healthy, the kind of person who simply didn't get sick. He helped many people over the years, and he raised four children.</p>

    <p>Years earlier, without anyone knowing, he had been exposed to asbestos. It stayed quiet for a long time while he kept living fully, kept working, kept helping people — until it turned into mesothelioma. When the symptoms finally came, they came fast — four or five months, and he was gone. It still doesn't feel like enough time to say goodbye to someone who seemed, right up until then, so strong.</p>

    <p>I hadn't been able to see him in the five years before he passed. That distance is something I carry alongside the grief itself — the things I didn't get to say to him in person, I am still learning how to say now.</p>
  </div>

  <blockquote>
    "[Optional — a quote, a line of poetry, or something he used to say]"
  </blockquote>

  <div class="memoriam-section-title">Through the years</div>

  <!--
    To add a photo: drop the file in assets/img/in-memoriam/ (e.g. young-1.jpg),
    then add a line like the one below inside memoriam-gallery, one per photo.
    Mix ages freely — the grid doesn't need to be in strict order.

    <figure>{% include figure.liquid path="assets/img/in-memoriam/young-1.jpg" class="img-fluid" alt="Kazem as a young man" %}</figure>
  -->
  <div class="memoriam-gallery">
  </div>
  <p class="memoriam-placeholder-note">(photos coming soon)</p>

  <div class="memoriam-section-title">Stories</div>

  <!--
    Each story is a short block. Copy this pattern for each one:

    <div class="memoriam-story">
      <div class="memoriam-story-title">A short title for the story</div>
      <p>The story itself, in a sentence or a few paragraphs.</p>
    </div>
  -->
  <div class="memoriam-stories">
    <p class="memoriam-placeholder-note">(stories coming soon)</p>
  </div>

</div>
