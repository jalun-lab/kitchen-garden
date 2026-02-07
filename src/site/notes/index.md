---
{"dg-publish":true,"permalink":"/index/","tags":["gardenEntry"]}
---

<div class="homepage-categories">
  <a href="/every-day-food" class="category-item">
    <img src="https://grimgrains.com/media/ingredients/lentils.png" alt="Lentils">
    <div class="category-title">Every Day Food</div>
  </a>

  <a href="/sometimes-food" class="category-item">
    <img src="https://grimgrains.com/media/ingredients/turmeric_root.png" alt="Turmeric">
    <div class="category-title">Sometimes Food</div>
  </a>
</div>

<div class="recipe-grid">

<div class="grid-column">
### MAINS
`dataview
LIST FROM "" 
WHERE course = "main" AND dg-publish = true
`
</div>

<div class="grid-column">
### SIDES & SNACKS
`dataview
LIST FROM "" 
WHERE (course = "side" OR course = "snack") AND dg-publish = true
`
</div>

<div class="grid-column">
### DESSERTS
`dataview
LIST FROM "" 
WHERE course = "dessert" AND dg-publish = true
`
</div>

</div>