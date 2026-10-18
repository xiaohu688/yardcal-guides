# YardCal — Home & Yard Calculator Guides

Practical measurement guides and material-planning worksheets for home and yard projects.

**[Open YardCal](https://yard-cal.com/)** · **[Browse all calculators](https://yard-cal.com/calculators)**

YardCal offers free online calculators for gravel, soil, mulch and home improvement projects. Use the website to estimate quantities, compare inputs and plan a material purchase. This repository contains public guides and reusable worksheets; it is not the source code of the YardCal website.

## Choose a calculator

| Your project | Calculator | What to prepare |
| --- | --- | --- |
| Gravel coverage | [Gravel Calculator](https://yard-cal.com/gravel-calculator) | Area, depth, material density and an allowance |
| Garden beds | [Topsoil Calculator](https://yard-cal.com/topsoil-calculator) | Bed dimensions and soil depth |
| Mulching | [Mulch Calculator](https://yard-cal.com/mulch-calculator) | Covered area, mulch depth and bag size |
| Sand coverage | [Sand Calculator](https://yard-cal.com/sand-calculator) | Area, depth and supplier density |
| Paver foundation | [Paver Base Calculator](https://yard-cal.com/paver-base-calculator) | Base footprint and planned layer depth |
| Raised beds | [Raised Bed Soil Calculator](https://yard-cal.com/raised-bed-soil-calculator) | Inside bed dimensions and fill depth |
| Deck planning | [Deck Planner](https://yard-cal.com/deck-builder) | Layout dimensions and selected construction options |
| Fence planning | [Fence Planner](https://yard-cal.com/fence-builder) | Run length and fence configuration |
| Concrete slab | [Concrete Slab Planner](https://yard-cal.com/concrete-slab-builder) | Slab dimensions and thickness |
| Painting | [Paint Planner](https://yard-cal.com/paint-builder) | Surface dimensions, openings and coverage assumptions |

For the full library, use [YardCal's calculator directory](https://yard-cal.com/calculators).

## Start with a measured estimate

1. Measure the actual footprint. Split an irregular area into smaller rectangles or circles.
2. Choose the intended layer depth and keep all measurements in consistent units.
3. Calculate volume, then add an explicit ordering allowance.
4. Use your supplier's density to convert volume to weight, if needed.
5. Compare the estimate with available bag sizes, delivery increments and local prices.

### Example: a rectangular gravel area

A 20 ft × 10 ft area at 3 in deep has a base volume of:

```text
Depth = 3 / 12 = 0.25 ft
Volume = 20 × 10 × 0.25 = 50 cubic feet
With an illustrative 10% allowance = 55 cubic feet
Cubic yards = 55 / 27 ≈ 2.04
0.5 cubic-foot bags = ceil(55 / 0.5) = 110 bags
```

The 10% allowance is an example, not a universal compaction factor. Use a supplier's guidance when the installed depth requires compacted material.

Try the same measurements in the [online gravel calculator](https://yard-cal.com/gravel-calculator).

## Free resources

- [Material estimating guide](guides/material-estimating.md): formulas, metric and imperial examples, ordering checks.
- [Material estimate worksheet](templates/material-estimate.csv): a CSV you can open in Excel, Google Sheets or a text editor. Values are a worked example, not live spreadsheet formulas.
- [Calculation methodology](https://yard-cal.com/methodology): how to interpret estimates on the website.

## Scope

These resources support quantity estimates and early planning. Material density, moisture, compaction, product coverage and delivery rounding can change an order. Project planners do not replace site measurements, manufacturer instructions, code checks or professional structural/electrical design.

## Contributing

Corrections and clearer examples are welcome. Open an issue or pull request with the affected guide, units, calculation steps and expected result. If suggesting a product-specific coverage rate, link to the manufacturer's published specification.

## License

The guides and worksheet in this repository are available under the [MIT License](LICENSE). This license applies to this repository's contents, not to the separate YardCal website code or third-party materials.

Built for people planning their next project with [YardCal](https://yard-cal.com/).
