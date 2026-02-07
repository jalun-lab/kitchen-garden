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
# THE RECIPE ARCHIVE

## BY MAIN COMPONENT
* **Chicken:**  recipes
* **Beef:**  recipes
* **Dairy/Dessert:**  recipes

---

## RECENT ADDITIONS

```dataview
TABLE WITHOUT ID
  file.link as "RECIPE",
  protein as "PROT.",
  calories as "KCAL",
  main_equipment as "EQUIPMENT"
FROM "Recipes"
WHERE dg-publish = true
SORT file.ctime DESC
LIMIT 10