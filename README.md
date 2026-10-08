# Awesome Concrete Calculators

A curated list of free concrete calculators, bag/yield guides, project quick-references, and volume formulas — for DIYers, contractors, and estimators.

## Online Calculators

| Calculator | What it covers |
|---|---|
| [ConcreteCalcus](https://concretecalcus.com/) | Free suite of 30 tools: slabs, footings, post holes, walls, columns, stairs, bag counts, rebar, block, gravel, and full cost estimation. No signup. |
| [ConcreteCalcus Slab Calculator](https://concretecalcus.com/slab/24x24/) | Rectangular slab volume in cubic yards/feet/meters, with waste buffer, rebar grid, saw-cut joints, and gravel subbase estimates. |
| [Inch Calculator — Concrete](https://www.inchcalculator.com/concrete-calculator/) | Slab, footing, post-hole, driveway, steps, and block calculators with detailed methodology notes. |
| [Concrete Network Calculator](http://www.concretenetwork.com/concrete/howmuch/calculator.htm) | Long-standing industry calculator for slabs and footings. |
| [Calculator.net — Concrete](https://www.calculator.net/concrete-calculator.html) | General-purpose volume calculator with slab, footing, wall, and column presets. |
| [Quikrete Calculator](https://www.quikrete.com/Calculator/) | Manufacturer calculator focused on bag counts (40/60/80 lb) for slabs, footings, and post holes. |

## Bag Sizes & Yield Guides

| Guide | What it covers |
|---|---|
| [ConcreteCalcus Bag Guide](https://concretecalcus.com/bags/) | Yield per bag size (40/50/60/80 lb), bags-per-yard tables, and a custom bag-count calculator including fractional bags. |

**Bag yields (per cubic foot of mixed concrete):**

| Bag size | Yield per bag | Bags per cubic yard |
|----------|---------------|---------------------|
| 80 lb    | 0.60 cu ft    | 45                  |
| 60 lb    | 0.45 cu ft    | 60                  |
| 50 lb    | 0.375 cu ft   | 72                  |
| 40 lb    | 0.30 cu ft    | 90                  |

## Common Projects — Quick Reference

Exact theoretical volume vs. recommended order quantity (+10% waste). Standard residential thickness is 4".

| Project | Exact volume | Order (+10%) | 80 lb bags |
|---|---|---|---|
| 10×10 ft patio, 4" thick | 1.23 yd³ | 1.36 yd³ | 56 |
| 12×12 ft patio, 4" thick | 1.78 yd³ | 1.96 yd³ | 80 |
| 12×16 ft shed slab, 4" thick | 2.37 yd³ | 2.61 yd³ | 107 |
| 16×30 ft pole-shed slab, 4" thick | 5.93 yd³ | 6.52 yd³ | 267 |
| 20×20 ft garage slab, 4" thick | 4.94 yd³ | 5.43 yd³ | 223 |
| Post hole 12" dia × 36" deep | 0.09 yd³ | 0.10 yd³ | 4 |
| Trench footing 16"w × 8"d × 50 ft | 1.65 yd³ | 1.81 yd³ | 75 |

## Core Formulas

**Slab (rectangular):**
```
Cubic Yards = Length (ft) × Width (ft) × (Thickness (in) ÷ 12) ÷ 27
```

**Post hole / cylinder:**
```
Cubic Feet = π × (Diameter (in) ÷ 24)² × (Depth (in) ÷ 12)
```

**Trench footing:**
```
Cubic Yards = (Width (in) ÷ 12) × (Depth (in) ÷ 12) × Length (ft) ÷ 27
```

**Wall:**
```
Cubic Yards = Length (ft) × Height (ft) × (Thickness (in) ÷ 12) ÷ 27
```

## Ordering Tips

1. **Always add 5–10% waste.** Subgrade is never perfectly level and forms deflect. 15% for rough hand-dug holes.
2. **Ready-mix vs. bags:** over ~1.5–2 cubic yards (60–90 eighty-pound bags), a ready-mix truck is cheaper, faster, and avoids cold joints.
3. **Short-load fees:** orders under ~4 yd³ often carry a $75–$120 short-load surcharge — combine pours when you can.
4. **Thickness matters more than you think:** on a 16×30 slab, the difference between 4" and 5" is 1.48 cubic yards.
5. **Slab thickness guide:** walkways 3.5–4", patios/shed floors 4", driveways 4–5", heavy truck/RV pads 5–6" with rebar.

## Companion Tool

A dependency-free, single-file version of the slab/post-hole/footing/wall calculator in this org:
**[concrete-volume-calculator](../concrete-volume-calculator)** — open `index.html`, no build step.

## Contributing

Suggestions welcome — open a PR with a free, working concrete calculator or estimating resource.

## License

MIT — see [LICENSE](LICENSE).
