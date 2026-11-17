# Costing: cost per cup, margin and markup

Worked out on 16 Nov 2026 from the owner's handwritten recipes (`uploads/recipes/`), the supplier orders (`uploads/price-list/`) and the owner's answers. Nothing in the POS (`pos/js/seed.js`) has been changed yet.

**Definitions.** Cost = ingredients + overhead ৳33 + cup. Profit = price − cost. Margin % = profit ÷ price. Markup % = profit ÷ cost. Food cost % = ingredients ÷ price.

Sizes: Medium = 350 ml (cup, lid and straw ৳21). Large = 500 ml (৳23). Overhead is a flat ৳33 per cup as written on the owner's sheets. Toppings (tapioca etc.) are not included.

## Unit prices used

| Item | Source | Unit cost |
|---|---|---|
| Scoop of powder | owner: 15 g | creamer ৳15, chocolate ৳18.75, taro ৳16.50, coconut powder ৳19.50 |
| Pump | owner: 10 ml | |
| Whole milk | ৳120/L | ৳0.12/ml |
| Evaporated milk | ৳200 per 380 ml | ৳0.526/ml |
| Whipping cream | ৳300 per 1000 g | ৳0.30/g (matches the ৳30 per 100 ml on the Biscoff sheet) |
| Sugar syrup | 1 kg sugar (৳105) + 1 L water | ৳0.07/ml (assumes about 1.5 L of syrup) |
| Brown sugar syrup | ৳1,300 per 1,300 g | ৳1.00/g (treated as 1 g = 1 ml) |
| Chocolate syrup | ৳500 per 1,400 g | ৳0.357/g |
| Coconut powder | ৳1,300/kg | ৳1.30/g |
| Creamer, chocolate, taro | invoices | ৳1.00, ৳1.25, ৳1.10 per g |
| Jam (mango, strawberry, mulberry) | invoices, ৳1,800 per 1.2 kg | ৳1.50/g |
| Blueberry jam | owner: ৳1,800 (size assumed 1.2 kg) | ৳1.50/g |
| Biscoff spread | ৳900 per 400 g | ৳2.25/g |
| Jasmine tea | ৳2,000 per 500 g | ৳4.00/g |
| Coconut jelly | = "Original Coconut Topping" | ৳0.95/g (1 kg) or ৳1.12/g (2.5 kg bucket) |

**Assumed, not confirmed:** a jam scoop weighs 30 g (taken from the carnation sheet: ৳70 for 1.5 scoops); "brown syrup 1 / 1½" means pumps; Premium Brown Sugar is a 500 ml drink.

## Results

| Drink | Size | Ingredients | Total cost | Price | Profit | Margin | Markup |
|---|---|---|---|---|---|---|---|
| Taro Coconut Milk Tea | M | 70 | 124 | 230 | 106 | 46% | 86% |
| Taro Coconut Milk Tea | L | 113 | 169 | 270 | 101 | 37% | 60% |
| Mango Blush | M | 82 | 136 | 190 | 54 | 29% | 40% |
| Mango Blush | L | 153 | 209 | 230 | 21 | 9% | 10% |
| The Very Berry | M | 123 | 177 | 230 | 53 | 23% | 30% |
| The Very Berry | L | 190 | 246 | 270 | 24 | 9% | 10% |
| Strawberry Bliss | M | 78 | 132 | 190 | 58 | 30% | 44% |
| Strawberry Bliss | L | 146 | 202 | 230 | 28 | 12% | 14% |
| Triple Choco Bliss | M | 75 | 129 | 200 | 71 | 36% | 55% |
| Triple Choco Bliss | L | 117 | 173 | 250 | 77 | 31% | 45% |
| Choco Berry Carnation | M | 174 | 228 | 340 | 112 | 33% | 49% |
| Choco Berry Carnation | L | 230 | 286 | 400 | 114 | 28% | 40% |
| Brown Sugar Milk Tea | M | 42 | 96 | 190 | 94 | 49% | 98% |
| Brown Sugar Milk Tea | L | 69 | 125 | 230 | 105 | 45% | 83% |
| Premium Brown Sugar | L | 118 | 174 | 300 | 126 | 42% | 72% |
| Biscoff Cookie Crumble | M | 90 | 144 | 240 | 96 | 40% | 67% |
| Biscoff Cookie Crumble | L | 126 | 182 | 290 | 108 | 37% | 59% |

Notes:
- Triple Choco and Carnation use the quantities on the owner's costing pages (confirmed as current). The Carnation result matches the owner's own total (৳229 and ৳289).
- Triple Choco includes ৳10 for chocolate syrup, as on the sheet. The ৳10 tapioca is not included.
- Biscoff uses the owner's totals: M 90 + 21 + 33 = 144, L 126 + 23 + 33 = 182. **Check needed:** Biscoff spread costs ৳900 per 400 g (৳2.25/g), so 40 g = ৳90 and 56 g = ৳126. These match the sheet's "90" and "126" exactly, so those numbers may be the spread alone. If so, add whipping cream (100 ml = ৳30), milk (90 ml = ৳11) and vanilla (5 ml), which makes Medium cost about ৳189 (margin about 21%).
- Overhead ৳33 per cup covers water, electricity and rent. It does not include wages.
- Recipes still missing: Peach, Mango, Passion Fruit and Strawberry & Lime Jasmine Tea, Lychee Paradise, Passion in Paradise, Mulberry Bliss, Blueberry Snow Bliss.

## Toppings (one serving per drink)

Serving sizes from the owner. Golden tapioca is discontinued (it is still in the POS and needs removing). The POS has one price per topping for both sizes, and none of these costs include overhead or cup.

| Topping | Price per g | Medium | Large | POS price | Profit M | Profit L |
|---|---|---|---|---|---|---|
| Black tapioca | ৳0.50 (dry, ৳500/kg) | 40 g = ৳20.0 | 55 g = ৳27.5 | ৳20 | ৳0.0 | −৳7.5 |
| Crystal ball | ৳1.10 (৳1,100/kg) | 32 g = ৳35.2 | 45 g = ৳49.5 | ৳40 | ৳4.8 | −৳9.5 |
| Popping ball | ৳1.417 (strawberry, ৳1,700 per 1.2 kg) | 32 g = ৳45.3 | 42 g = ৳59.5 | ৳50 | ৳4.7 | −৳9.5 |
| Coconut jelly | ৳0.95 (1 kg, ৳950) | 30 g = ৳28.5 | 43 g = ৳40.9 | ৳30 | ৳1.5 | −৳10.9 |

Notes:
- Crystal ball price is the cold cream and strawberry flavours (both ৳1,100/kg). Pomelo has no invoice.
- Popping ball price is strawberry only. Mango, passion fruit and lychee have no invoice.
- Coconut jelly from the 2.5 kg bucket (৳2,800) would cost ৳1.12/g, so ৳33.6 (M) and ৳48.2 (L).
- Unconfirmed: whether the tapioca weights are dry or cooked. The owner's Triple Choco sheet used ৳10 for tapioca, which is 20 g dry.
