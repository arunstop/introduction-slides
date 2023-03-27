---
layout: cover
background: https://sli.dev/demo-cover.png
transition: slide-left
---

# Introduction of Arunseto Pambudi

This is a very good keynote, if you have a bad taste.

---
theme: seriph
transition: slide-left
layout: cover
background: https://sli.dev/demo-cover.png
class : text-center
---

# What is it?

The moniker Arunseto Pambudi can be defined as such :
---
theme: seriph
transition: slide-left
layout: cover
background: https://cdn.britannica.com/36/79536-050-BE1C475B/human-lineage-hominins-members-lineages-apes-interpretations.jpg
class : text-center
---
# Homo Sapiens

Most commons race of humans on Earth
---
theme: seriph
transition: slide-left
layout: cover
background: https://cdn.britannica.com/36/79536-050-BE1C475B/human-lineage-hominins-members-lineages-apes-interpretations.jpg
class : text-center
---
# Male

XY
---
theme: seriph
transition: slide-left
layout: cover
background: https://cdn.britannica.com/71/145971-050-A850F4CB/Ruins-temple-Doric-Selinus-Sicily.jpg
class : text-center
---

# 24 years old Creature

Has been existing (thankfully) for 25 years on this Earth
---
theme: seriph
transition: slide-left
layout: cover
background: https://media.tenor.com/2qcQO7l8f5AAAAAM/froggy-dance.gif
class : text-center
---

# Hyperactive Creature

Very active or sometimes abnormally active.

---
theme: seriph
transition: slide-left
layout: cover
background: https://upload.wikimedia.org/wikipedia/commons/5/5a/Covid-19_spread_timeline_in_Indonesia.gif
class : text-center
---

# Indonesian

Biggest SEA country, SEA big bro.

---
theme: seriph
transition: slide-left
layout: cover
background: https://media.tenor.com/ucrXwec7sfcAAAAC/fng-mutiny.gif
class : text-center
---

# F. N. G.

---
theme: seriph
transition: slide-left
layout: cover
background: https://media.tenor.com/rf88Pwf2KcsAAAAC/css-ie.gif
class : text-center
---

# Frontend New Guy

HTML + CSS + Javascript goes BRRRRRRRRRRRRRR

---
theme: seriph
transition: slide-left
layout: cover
background: https://thumbs.gfycat.com/AnimatedDeficientAlleycat-size_restricted.gif
class : text-center
---

# REASON TO EXIST

Every creature that exist in this world, must have a reason to exist, right?

---
theme: seriph
transition: slide-left
layout: cover
background: https://asset.kompas.com/crops/O3kKNUL06rj-5sU-mzhYwvJpcS4=/44x8:1000x645/750x500/data/photo/2019/12/18/5df9e59f4c8b0.jpg
class : text-center
---

# Food

Enjoying food = Enjoying life

---
theme: seriph
transition: slide-left
layout: cover
background: https://thumbs.gfycat.com/IgnorantHarmfulChrysalis-small.gif
class : text-center
---

# Ending Of One Piece

Please pray to Oda's health.
---
theme: seriph
transition: slide-left
layout: cover
background: https://64.media.tumblr.com/7784071b39cd25a817a543bc8c169f07/7bf7bb69801675b5-f5/s540x810/99ce3f9f3f29e0ec08e1f4311c5ef5dc03d8483f.gif
class : text-center
---

# Dune Trilogy

Let's hope they don't butcher this one.
---
theme: seriph
transition: slide-left
layout: cover
background: https://64.media.tumblr.com/7784071b39cd25a817a543bc8c169f07/7bf7bb69801675b5-f5/s540x810/99ce3f9f3f29e0ec08e1f4311c5ef5dc03d8483f.gif
class : text-center
---

# History

Let's hope they don't butcher this one.

---
preload: false
---

# Animations

Animations are powered by [@vueuse/motion](https://motion.vueuse.org/).

```html
<div
  v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
  Slidev
</div>
```

<div class="w-60 relative mt-6">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-square.png"
    />
    <img
      v-motion
      :initial="{ y: 500, x: -100, scale: 2 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-circle.png"
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>

  <div
    class="text-5xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Slidev
  </div>
</div>

<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 40, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }">

[Learn More](https://sli.dev/guide/animations.html#motion)

</div>
---
layout: center
class: text-center
---

# That's it...

<div>Made with Sli.dev</div>
<a>https://sli.dev</a>
