---
layout: default
title: "An Alaskan serial adventure in IT..."
fallback_episode: "/sample/"
---

<article class="post-article">
  <div class="continue-panel" data-continue-panel>
    <header class="post-article__header">
      <h1 class="post-article__title">{{ page.title }}</h1>
    </header>
    <div class="post-article__content">
      <p data-continue-message>Start with Episode 001.</p>
      <a class="continue-panel__cta" data-continue-link data-fallback="{{ page.fallback_episode }}" href="{{ page.fallback_episode }}">Get started with Episode 001...</a>
      <p class="continue-panel__note"></p>
    </div>
  </div>
</article>