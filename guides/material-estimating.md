# Material estimating: from dimensions to an order

Use this guide with the [YardCal material calculators](https://yard-cal.com/calculators).

## 1. Measure the footprint

For a rectangle, area = length × width. For a circle, area = π × (diameter / 2)². For an irregular footprint, sum the areas of measured sections and subtract areas you will not fill. Avoid overlapping sections.

Use inside dimensions for a raised bed. Note slopes and uneven ground; a single average depth can hide a large difference in material needs.

## 2. Calculate a consistent volume

For imperial measurements:

```text
Depth in feet = depth in inches / 12
Cubic feet = area in square feet × depth in feet
Cubic yards = cubic feet / 27
```

For metric measurements:

```text
Depth in meters = depth in centimeters / 100
Cubic meters = area in square meters × depth in meters
Liters = cubic meters × 1000
```

A 6 m × 3 m bed with a 5 cm layer needs 6 × 3 × 0.05 = 0.9 m³ before any allowance.

## 3. Separate base volume from ordering allowance

```text
Order volume = base volume × (1 + allowance percent / 100)
```

With an illustrative 10% allowance, the metric example becomes 0.99 m³, or 990 liters. Do not automatically add the same allowance again when your supplier has already provided a loose-to-compacted conversion. An allowance is not a substitute for a verified compaction factor.

## 4. Convert volume to weight only with a suitable density

```text
Mass in kilograms = cubic meters × bulk density in kg/m³
Metric tonnes = kilograms / 1000
US short tons = pounds / 2000
```

A metric tonne and a US short ton are different units. Use the density and moisture basis supplied for the actual material. Decorative gravel, sand, topsoil and mulch do not share one universal density.

## 5. Round a bag order up

```text
Bags = ceil(order volume / volume per bag)
```

Use matching volume units. For the 990-liter example and 50-liter bags, ceil(990 / 50) = 20 bags. This gives 1000 liters of purchased capacity. A bag labeled only by weight requires a compatible density estimate before it can be compared with a volume requirement.

## 6. Price the correct purchase quantity

For bagged material, multiply the rounded bag count by price per bag. For bulk material, ask the supplier about minimum orders and delivery increments before multiplying by the unit price. Add delivery and taxes separately.

## Record the estimate

The [CSV worksheet](../templates/material-estimate.csv) includes the 20 ft × 10 ft × 3 in example from the [README](../README.md). Duplicate the row and replace all inputs and calculated outputs for your project; the CSV does not recalculate itself.

Use [YardCal](https://yard-cal.com/) for interactive calculations, and confirm final ordering quantities with your supplier.
