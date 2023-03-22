---
title: Websites
tagline: Websites
layout: post
description: Websites from a backend guy.
website:
  amita-kullaphan-com:
    image: 
      name: amita-kullaphan-com.png
      align: right
  trackmasters-cz:
    image:
      name: trackmasters-cz.png
      align: right

---
Aside from my simple Jekyll website, I've created a couple more.

---

## [amita-kullaphan.com](https://amita-kullaphan.com)

<a href="https://www.amita-kullaphan.com">
  <img class="{{ page.website.amita-kullaphan-com.image.align }}" alt="amita-kullaphan.com" width="34%"
       src="{{ page.website.amita-kullaphan-com.image.name | prepend: '/assets/images/websites/' | relative_url }}">
</a>

A personal website free of charge for this beautiful lawyer was built on Hugo, hosted on GitHub Pages, and deployed by the Actions.

I had only a small experience with Jekyll static site generator. 
Regarding Ruby, its package management, and gems, I had zero experience - this hasn’t changed over time, though. 
So I decently asked her to choose a Jekyll template from [jamstackthemes.dev](https://jamstackthemes.dev/theme/).
Despite knowing how women choose, I got horrified once I learned she showed me the [Portio Hugo template](https://jamstackthemes.dev/theme/portio-hugo/).

I had no choice but to meet Hugo and convince him to build a website for her using this fabulous theme. 
Surprisingly, navigating through the files and configuration was simple: 
I made a few changes, such as removing the Portfolio, Testimonials, and Blog sections, as well as designing and writing most of the content. 
In less than three Saturday afternoons, the website was ready for domain purchase, which led to another afternoon full of DNS configuration, website fine-tuning, and CORS hassle.

I am particularly proud of the custom icons I drew in Inkscape you can find in the [Legal Service](https://www.amita-kullaphan.com/#service) section.

___


## [trackmasters.cz](https://trackmasters.cz)

<a href="https://www.trackmasters.cz">
  <img class="{{ page.website.trackmasters-cz.image.align }}" alt="trackmasters.cz" width="34%"
       src="{{ page.website.trackmasters-cz.image.name | prepend: '/assets/images/websites/' | relative_url }}">
</a>

To be written soon...

<!--
Jekyll template: <span class="fab fa-github" style='font-size:30px'></span> [Gradfolio](https://github.com/jitinnair1/gradfolio), see the live [demo](https://jitinnair1.github.io/gradfolio)

Footer icons: <span class="fab fa-github" style='font-size:30px'></span> [Modern Resume](https://github.com/sproogen/modern-resume-theme), see the live [demo](https://sproogen.github.io/modern-resume-theme)
-->