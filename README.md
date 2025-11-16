# 1.05 TW Legendary Fusion Plant

Beltless, Logistics-fed **~1.0–1.05 TW** fusion power plant built with legendary quality:

* **740 × Legendary Fusion Reactors**
* **~8,400 × Legendary Fusion Generators**

This design is **buildable everywhere except Aquilo and the Space Platform**. Reactors are fueled via the **logistic network.**

---

## Highlights

* **Throughput:** ~**1.0 TW** sustained (cap ~**1.05 TW** with 8.4k gens)
* **Fueling:** Logistic bots, Requester chest per reactor
* **Coolant:** Fluoroketone closed loop with external cooling
* **Start-safe:** One-click kickstart, self-powering after spin-up

---

## Requirements

* Surfaces: **Any except Aquilo and Space Platform**
* Tons of logistic bots.
* Legendary quality (Fusion Reactors and its Generators, Speed Modules 3, Beacons, Substations, Cryogenic plants, Assembling Machine 3) 
* A fluoroketone cooling plant sized for the stated loop rates

---

## Plant Specs & Sizing

### Nameplate vs Target

* **Generator ceiling:** 8,400 × 125 MW ≈ **1.05 TW** (nameplate)
* **Operating target:** **1.00 TW** (≈95.25% load factor)

### Fuel: Fusion Power Cells

* **Kickstart:** **740 cells**
* **Sustain @ 1.00 TW (gross):** **≈ 106 cells/min** or **≈ 6,343 cells/hour** or **≈ 152,000 cells/day**
* **If you want ~1.00 TW *net*** after reactor idle drain:
  Reactors draw **~7.4 GW** total when idle; target **~1.007 TW** gross.
  That nudges consumption to **≈ 6,388 cells/hour**.

### Coolant: Fluoroketone

Reminder: FK is recirculated, not consumed. You need to seed the loop and cool it.

* **Operating flow @ 1.00 TW:** ≈ **7,050 FK/s** circulating
* **Practical seed volume:** **700–1,400 barrels** (≈ **35k–70k FK**)
  Enough to fill pipes/buffers so the loop is stable during spin-up.
* **Absolute minimum to just to kickstart:** ~**740 barrels** (1 per reactor).
  Works, but spin-up is touchier and more prone to starvation.
* **Fill all buffers (theoretical, not required):** ~**31,600 barrels**
  Only relevant if you deliberately over-buffer every machine and pipe.

> Rule of thumb: size cryo/cooling arrays for ≥ the loop heat at 1.0 TW with ~20% margin. Split the plant into multiple independent FK loops to localize faults and shorten pipe runs.
