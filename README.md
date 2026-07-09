# Isolation and Purification of Recombinant Protein

**Group 1:** Akshaya · Sunandini · Srihari · Sabareesh · Subitcha

## Overview

This project documents the end-to-end workflow for expressing and analyzing
two recombinant constructs — **PS107** and **GFP** — in *E. coli* BL21(DE3).
It covers everything from media preparation through bacterial transformation,
IPTG-induced protein expression, and SDS-PAGE analysis, including two rounds
of optimization (IPTG concentration and induction duration).

**Duration:** June 1–23, 2023

## Workflow

1. Broth/agar preparation and calculations
2. LB broth and agar media prep
3. Competent cell preparation
4. Bacterial transformation
5. Transformation efficiency calculation
6. Colony streaking and purification
7. IPTG induction (PS107 and GFP)
8. Microscopic and UV visualization
9. Protein isolation via sonication/lysis
10. SDS-PAGE analysis
11. Optimization of IPTG concentration and induction time

## Materials Used

- Conical flasks, measuring flasks, cotton plugs, autoclave
- LB broth (25 g/L) and LB agar (15 g/L)
- Kanamycin50, Ampicillin
- BL21(DE3) competent *E. coli* cells, plasmid PS107
- Shaking incubator, centrifuge, water bath, ice
- 0.1 M CaCl₂, 1 mM IPTG
- SDS-PAGE apparatus: glass plates, spacers, comb, Vaseline, TGS buffer, paper clips
- Coomassie Brilliant Blue R-250 stain, de-staining solution
- Compound microscope, UV lamp

## Procedure

### 1. LB Broth & Agar Preparation (06/01–06/02)
LB broth was prepared at 25 g/L for 60 mL and 100 mL batches, and LB agar at
15 g/L, using calculated weights of powder made up to volume with distilled
water. Flasks were sealed with cotton plugs and autoclaved for ~2 hours at
121 °C, 15 psi.

### 2. Bacterial Inoculation (06/05)
A single colony of BL21(DE3) was inoculated into 5 mL of LB broth with
antibiotic and grown overnight in a shaker at 37 °C, 150 rpm.

### 3. Competent Cell Preparation (06/06)
- 1% of the overnight culture was transferred into 10 mL fresh LB broth and
  grown until OD₆₀₀ reached 0.4.
- Cells were pelleted by centrifugation (5000 rpm, 10 min, 4 °C), resuspended
  in ice-cold 0.1 M CaCl₂, and incubated on ice for 30 min.
- Cells were pelleted again, resuspended in 500 µL of 0.1 M CaCl₂, aliquoted
  into 100 µL portions, and stored at 4 °C.

### 4. Bacterial Transformation (06/07)
- 5 ng (2 µL) of plasmid PS107 was mixed with 100 µL of thawed competent
  cells and incubated on ice for 30 min.
- Cells were heat-shocked at 42 °C for 90 s, then returned to ice for 5 min.
- 1000 µL of fresh LB medium was added, followed by 1 hour of recovery in a
  shaker at 37 °C, 150 rpm.
- 100 µL of the recovered mixture was plated on LB + Kanamycin50 plates and
  incubated overnight (16 hrs) at 37 °C.

**Colony counts obtained:**

| Member     | Colonies |
|------------|----------|
| Subitcha   | 112      |
| Sabareesh  | 46       |
| Srihari    | 33       |
| Sunandini  | 23       |

### 5. Transformation Efficiency (06/08)
Using the standard formula:

```
TE = No. of colonies × (Total volume of transformed culture /
     Volume of transformed culture plated) × (1000 / ng plasmid used)
```

Example calculation (Sabareesh's plate, 46 colonies):

```
46 × (1100/100) × (1000/100) = 5,060 CFU/µg  ≈ 5.06 × 10³
```

### 6. Colony Streaking (06/08–06/09)
Individual colonies were streaked onto fresh LB + Kanamycin50 plates and
incubated overnight at 37 °C to obtain pure, isolated colonies (Fig. 5a–5e).

### 7. Mother Culture Prep & IPTG Induction — PS107 (06/12)
- Media was prepared in 20 mL, 50 mL, and 60 mL batches; a mother culture was
  grown from a streaked colony.
- 1% mother culture was added to fresh LB + Kanamycin50 and grown to
  OD₆₀₀ = 0.4.
- Cultures were induced with 1 mM IPTG (0.119 g calculated for the batch) and
  incubated a further 4 hours at 37 °C.
- Post-induction, cells were pelleted (10,000 rpm, 5 min) and stored at
  –80 °C.

### 8. IPTG Induction — GFP (06/13)
The same protocol was repeated for the GFP construct, substituting
ampicillin for kanamycin and sampling at 2, 3, 4, and 20-hour induction
time points.

### 9. Microscopic Visualization (06/13)
Serial dilutions of the mother culture were viewed at 400x and 1000x
magnification, revealing rod-shaped bacterial cells consistent with healthy
*E. coli*.

### 10. GFP Visualization Under UV (06/13)
Induced GFP samples were examined under UV light. The 20-hour sample showed
the strongest green fluorescence, indicating the highest level of GFP
expression among the tested time points.

### 11. SDS-PAGE — Round 1 (06/14–06/15)
- 12% resolving gel (10 mL) and 5% stacking gel (5 mL) were cast, sealed with
  Vaseline, and leak-tested with water.
- Pellets were resuspended in water and mixed with 2x loading dye (with
  xylene cyanol), boiled for 10 min, cooled, and centrifuged.
- Samples loaded: protein ladder, uninduced GFP, GFP at 2/4/20 hrs,
  uninduced PS107, induced PS107.
- Run for ~2 hours, then stained with Coomassie Brilliant Blue R-250 and
  de-stained overnight.

**Result:** Thick bands appeared for induced GFP samples in the 25–35 kDa
range, confirming successful IPTG induction. A faint band was also visible
for induced PS107, suggesting only modest induction at 4 hours.

### 12. SDS-PAGE — Round 2 (06/15–06/16)
A second gel (12% resolving/8 mL, 5% stacking/3 mL) was run with additional
PS107 replicates alongside uninduced/induced GFP. Analysis the next day
showed a clear thick band for induced GFP and a thinner but visible band for
induced PS107, along with a faint band in the uninduced PS107 lane —
consistent with leaky basal expression from the T7-lac promoter system even
without IPTG.

### 13. Optimization Studies (06/19–06/23)

**IPTG concentration:** GFP was induced at 0.5, 1, 1.5, and 2 mmol IPTG.
The strongest induced band was observed at **1 mmol**.

**Induction duration (short range):** PS107 was induced for 2, 4, 6, and
16 hours. The strongest band was seen at **16 hours**.

**Induction duration (extended range):** PS107 was induced for 16, 24, and
48 hours. The strongest band was seen at **48 hours**, indicating that
longer induction continued to increase protein yield within the range
tested.

## Key Findings

- Transformation of PS107 into BL21(DE3) was successful, with transformation
  efficiencies on the order of 10³ CFU/µg across replicates.
- IPTG induction successfully drove expression of both GFP and PS107, visible
  both as green fluorescence under UV (GFP) and as distinct bands on
  SDS-PAGE (25–35 kDa range).
- 1 mmol IPTG produced the strongest induction among concentrations tested.
- Longer induction times (up to 48 hours, the longest tested) continued to
  increase visible protein yield for PS107.
- A faint band in uninduced samples indicates some baseline "leaky"
  expression from the T7-lac promoter system, which is expected in
  BL21(DE3)-based expression systems.

## Notes

This README summarizes the lab protocol and results captured across the
project's slide deck (dated 01/06/2023–23/06/2023), consolidating the
materials, step-by-step procedures, calculations, and gel interpretations
from each stage into a single reference document.
