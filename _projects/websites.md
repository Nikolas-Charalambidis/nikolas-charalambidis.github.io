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

My website is built on top of [Gradfolio](https://github.com/jitinnair1/gradfolio) Jekyll template with color and styles adjustments including the footer icons inspired by [Modern Resume](https://github.com/sproogen/modern-resume-theme).
Aside from my simple Jekyll website, I’ve created a couple more.

---

## [trackmasters.cz](https://trackmasters.cz)

<span class="fab fa-github" style='font-size:30px'></span> <a href="https://github.com/trackmasters/trackmasters.github.io">Source</a>

<a href="https://www.trackmasters.cz">
  <img class="{{ page.website.trackmasters-cz.image.align }}" alt="trackmasters.cz" width="34%"
       src="{{ page.website.trackmasters-cz.image.name | prepend: '/assets/images/websites/' | relative_url }}">
</a>

A website about the yearly track cycling cup in Prague. Track cycling is an interesting but dangerous sport itself: I occasionally rode until I slid off and burned my butt. 
The one who took me there, and who requested the website, was the same person: My younger and only brother. 
It prompted me automatically charge him at least double. 

The website was created with React.js because I wanted to practice this [framework/library](https://www.freecodecamp.org/news/is-react-a-library-or-a-framework/) on a real-life project as I only encountered it at the university.
I wish I had known Jekyll and other static site generators beforehand for numerous reasons:
GitHub Pages are not particularly friendly with React Router, and my CSS skills were, are, and will always be disastrous.

I spent some good quality time exploring and configuring Webpack and making the bloatware plugins, dependencies, and configurations talk to each other.
Finally, I made a website with reasonably simple custom content management that my not-tech-savvy brother can easily contribute through GitHub.
Nevertheless, I am glad I could finish a React project from scratch by myself.
