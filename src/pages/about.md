---
layout: ../layouts/AboutLayout.astro
title: "About"
---

Industrial Engineer building software. Sports enthusiast.

<!-- ![Astro Paper](public/astropaper-og.jpg) -->

<!-- ---
layout: ../layouts/AboutLayout.astro
title: "About"
description: "Vienna ↔ London. iOS architect turned web developer. Open source everything. Conference speaker & writer on tech innovation."
--- -->

import NewsletterForm from '../components/NewsletterForm.astro';

<div class="flex flex-col md:flex-row gap-8 items-start">
  <div class="w-full md:w-auto md:flex-shrink-0 md:max-w-[281px]">
    <img src="/picture-leo.jpg" alt="Peter in his office setup" class="w-full h-auto rounded-lg" />
  </div>
  <div class="flex-1 min-w-0">
    <p>Industrial Engineer building software. Sports enthusiast.</p>
  </div>
</div>

<!-- ## GitHub Activity

<div class="bg-secondary p-0 rounded-lg">
  <img 
    src="https://ghchart.rshah.org/leotraven" 
    alt="Peter's GitHub Contribution Graph" 
    class="w-full"
    style="max-width: 100%; height: auto;"
    loading="lazy"
  />
</div> -->

#### Stay Connected

<NewsletterForm />

If you'd like to connect or have questions about my work, feel free to reach out through any of the links below.


<!-- <div class="not-prose">
  <p class="text-sm text-gray-500 dark:text-gray-400 mt-8">Imprint: Peter Steinberger, Siebensterngasse 15, 1070 Vienna, Austria</p>
</div> -->