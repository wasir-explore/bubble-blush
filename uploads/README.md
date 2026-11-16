# Uploads: recipes and price list

Drop your source files here so profit margin and markup can be worked out from your real numbers.

| Folder | Put here |
|---|---|
| `recipes/` | Recipes per drink and size: ingredients with quantity (g / ml / pcs per cup). |
| `price-list/` | Inventory / supplier price list: ingredient, pack size, pack price. |

## Accepted formats
CSV, Excel (.xlsx), PDF, or clear photos/screenshots. CSV or Excel is best.

## Suggested columns
- Recipes: `drink, size, ingredient, quantity, unit`
- Price list: `ingredient, pack size, unit, pack price, supplier (optional)`
- Optional: your current selling price per drink and size, so margin can be compared with the menu.

## What I can work out from them
- Cost per cup for each drink and size
- Original profit margin (selling price minus cost) and food-cost %
- Markup % (profit over cost) and the price needed to hit a target margin
- Differences from the estimates currently in `pos/js/seed.js`

After uploading, commit/push to `main` and tell me, and I will use the files.
