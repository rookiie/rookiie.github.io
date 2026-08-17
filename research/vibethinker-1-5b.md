---
layout: profile
permalink: /research/vibethinker-1-5b/
redirect_from:
  - /blog/vibethinker-1-5b/
title: "VibeThinker-1.5B: Tiny Model, Big Logic"
excerpt: "A project note on diversity-driven optimization and reasoning in compact language models."
nav_active: research
---

<article class="blog-article research-article">
  <a class="blog-back" href="{{ '/research/' | relative_url }}"><span aria-hidden="true">←</span> All research</a>

  <header class="blog-article__header">
    <p class="blog-article__meta">Featured research · 2025 · Foundation models</p>
    <h1>VibeThinker-1.5B: Tiny model, big logic</h1>
    <p class="blog-article__lead">Can a compact language model develop reasoning ability usually associated with much larger systems? VibeThinker-1.5B explores that question through diversity-driven post-training.</p>
    <div class="research-entry__links research-article__links">
      <a href="https://arxiv.org/pdf/2511.06221" target="_blank" rel="noopener">Read the paper <span aria-hidden="true">↗</span></a>
      <a href="https://github.com/WeiboAI/VibeThinker" target="_blank" rel="noopener">View the code <span aria-hidden="true">↗</span></a>
    </div>
  </header>

  <figure class="blog-article__figure">
    <img src="{{ '/images/VibeThinker1_5B.png' | relative_url }}" width="791" height="424" alt="Benchmark comparison between VibeThinker-1.5B and larger reasoning models">
    <figcaption>VibeThinker-1.5B reasoning benchmark comparison.</figcaption>
  </figure>

  <div class="blog-article__body">
    <h2>The question behind the project</h2>
    <p>Reasoning performance is often associated with model scale. Our work asks whether targeted post-training and greater diversity in optimization data can help a much smaller model acquire stronger reasoning behavior.</p>

    <aside class="blog-article__callout">
      <span>At a glance</span>
      <strong>1.5B parameters</strong>
      <p>An open-source compact reasoning model developed through diversity-driven optimization.</p>
    </aside>

    <h2>Why this is worth sharing</h2>
    <p>Beyond the benchmark results, the project reflects a broader research direction: capability gains do not have to come only from increasing parameter count. Data design and post-training strategy can be equally important parts of the system.</p>

    <h2>Paper and code</h2>
    <p>The paper and open-source implementation contain the complete method, experiments, and evaluation.</p>
    <div class="blog-article__links">
      <a href="https://arxiv.org/pdf/2511.06221" target="_blank" rel="noopener">Read the paper <span aria-hidden="true">↗</span></a>
      <a href="https://github.com/WeiboAI/VibeThinker" target="_blank" rel="noopener">View the code <span aria-hidden="true">↗</span></a>
    </div>
  </div>
</article>
