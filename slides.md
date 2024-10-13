---
# You can also start simply with 'default'
theme: dracula
title: Animate.css Demo
info: Animations with CSS.
author: Ragib Asif
layout: cover
transition: fade
titleTemplate: '%s'
---

# Animate.css _[Demo](https://animatecssdemo.netlify.app/)_

## Presented by **Ragib Asif**

<br>

<Toc></Toc>

<div class="abs-br m-6 flex gap-2">
  <a href="https://linkedin.com/in/ragibasif/" target="_blank" title="LinkedIn" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white"> 
    <carbon-logo-linkedin />
  </a>
  <a href="https://github.com/ragibasif" target="_blank" alt="GitHub" title="GitHub" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>



---
title: What is Animate.css?
transition: fade-out
---

# What is Animate.css?



Animate.css is a versatile library of pre-made, cross-browser animations that can be easily added to web projects. 

It’s perfect for adding emphasis, enhancing homepages, creating sliders, and drawing attention to specific elements.

<br>

Read more about [Animate.css](https://animate.style/)


---
title: Installation
transition: slide-up
---

# Installation

Add the CDN link to your HTML:

```html
<head>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
</head>
```


---
title: Usage
transition: slide-right
---


# Usage 

Add the class `animate__animated` to an element, along with any of the animation names.

<div v-click>

```html
<h1 class="animate__animated animate__bounce">An animated element</h1>
```

</div>

<br>

<v-click>

The `animate__` prefix 
The <span v-mark.red="2"><code>animate__</code> prefix</span>
contains 
<span v-mark.circle.orange="4">two underscores.</span>

</v-click>


---
title: Global and Local Variables
transition: slide-left
---

# Global and Local Variables

You can also use CSS variables to define the animation's duration, delay, and iterations.

<v-click>

```css
/* This only changes this particular animation duration */
.animate__animated.animate__bounce {
  --animate-duration: 2s;
}

/* This changes all the animations globally */
:root {
  --animate-duration: 800ms;
  --animate-delay: 0.9s;
}
```

</v-click>