---
{"dg-publish":true,"permalink":"/index/","tags":["gardenEntry"]}
---


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