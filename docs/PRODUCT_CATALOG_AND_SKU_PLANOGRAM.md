# RoboPod 24/7: Product Catalog & SKU Planogram

---

## 1. Merchandising Strategy

As per strategic design decisions, **hot/warm items are excluded from Phase 1** to eliminate complex heating cycles, grease/odor ventilation requirements, and elevated health inspection hurdles. 

Instead, the catalog focuses on high-margin, fast-moving items across two core thermal zones:
1. **Chilled Zone (2°C – 4°C / 35°F – 39°F)**: Cold beverages, dairy, fresh fruit, and ready-made chilled grab-and-go meals.
2. **Ambient Zone (18°C – 21°C / 64°F – 70°F)**: Salty snacks, confectionery, bakery goods, and everyday convenience/emergency non-food essentials.

```
Total Inventory Capacity (20-ft High-Cube):
- Unique SKUs: ~520 distinct items
- Total Unit Count: ~4,200 packaged units
- Average Inventory Turns: 3.5 to 5.0 days per full restocking cycle
```

---

## 2. Category Breakdown & SKU Allocation

| Category | Shelf Space % | Typical SKUs | Packaging Standard | Unit Price Range | Gross Margin |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Cold Beverages & Sodas** | 30% | Pepsi, Pepsi Zero, Mountain Dew, Coca-Cola, Red Bull, Monster, Gatorade, iced teas, spring water, sparkling water | 355ml cans, 500ml/591ml PET bottles | $1.99 – $3.99 | 55% – 65% |
| **Ready-Made Fresh Grab & Go** | 20% | Artisan triangle sandwiches (turkey, ham, veggie), protein wraps, chef salads, yogurt parfaits, cheese & cracker snack packs | Rigid tamper-evident triangular or rectangular clamshells | $4.99 – $8.99 | 45% – 52% |
| **Fresh Produce & Dairy** | 10% | Bananas (cradled 2-3 count), crisp apples, peeled orange slices, 500ml & 1L 2% milk, chocolate milk, oat milk | Ventilated bio-trays with barcodes, HDPE cartons | $1.49 – $4.29 | 40% – 50% |
| **Salty & Savory Snacks** | 18% | Lay's, Doritos, Cheetos, pretzels, gourmet popcorn, roasted almonds, beef jerky | Nitrogen-flushed pillow bags (up to 120g) | $1.89 – $3.49 | 50% – 60% |
| **Confectionery & Bars** | 12% | Snickers, KitKat, M&Ms, Lindt bars, protein bars (Clif, RXBar), chewing gum | Flow-wrapped bars, peg bags | $1.79 – $3.49 | 55% – 65% |
| **Everyday Essentials & OTC** | 10% | Tylenol, Advil, band-aids, lip balm, tissues, phone charging cables, USB-C blocks, hand sanitizer | Small cardboard boxes, blister packs | $2.99 – $14.99 | 60% – 75% |

---

## 3. Planogram Racking Specifications (20-ft High-Cube Interior)

```
========================================================================================
WALL A (LEFT): CHILLED ZONE (2°C - 4°C) - 8 TIERS VERTICAL
========================================================================================
Tier 8 (Top)     : Lightweight yogurt cups, cheese sticks, snack packs
Tier 7           : Ready-to-eat salads & fruit cups (rigid clamshells)
Tier 6           : Triangle sandwiches & protein wraps (upright gravity slides)
Tier 5           : Fresh bananas (2-pack padded bio-trays) & apples
Tier 4           : Energy drinks & specialty teas (Red Bull, Monster, AriZona)
Tier 3           : Carbonated sodas (Pepsi, Pepsi Zero, Diet, Ginger Ale - 355ml cans)
Tier 2           : Bottled waters & sports drinks (500ml / 591ml PET bottles)
Tier 1 (Bottom)  : Heavy 1L milk jugs, chocolate milk, cold-brew coffee (high weight)
========================================================================================

========================================================================================
WALL B (RIGHT): AMBIENT ZONE (18°C - 21°C) - 8 TIERS VERTICAL
========================================================================================
Tier 8 (Top)     : Gum, mints, pocket tissues, lip balm, small OTC medicine packets
Tier 7           : Chocolate bars, gummy packs, confectionery boxes
Tier 6           : Protein bars, granola bars, trail mix pouches
Tier 5           : Dry bakery: muffins, cookies, croissants, bagels (wrapped)
Tier 4           : Premium nuts, dried fruit, beef jerky pouches
Tier 3           : Small & medium chip bags (Doritos, Lay's, Miss Vickie's)
Tier 2           : Large chip bags, pretzels, popcorn
Tier 1 (Bottom)  : Non-food essentials: phone chargers, power banks, umbrellas, ponchos
========================================================================================
```

---

## 4. Packaging & Dispense Engineering Rules

To ensure 99.98% pick reliability with zero robotic jams:
1. **Rigid Clamshell Standardization**: All delicate fresh foods (sandwiches, salads, fruit bowls) must use standardized PET or bagasse clamshells with a minimum top surface area of 6cm x 6cm for vacuum suction engagement.
2. **Gravity-Feed Roller Sliders**: Beverage cans and bottles sit on 8-degree sloped stainless steel roller tracks. A pneumatic gate dispenses exactly one container at a time onto the gantry receiver, eliminating mechanical jams.
3. **Automated Expiry Date Tracking**: Each perishable item has a serialized GS1 DataMatrix code containing its expiration date. The central management software automatically suppresses and quarantines items 6 hours prior to expiration.
