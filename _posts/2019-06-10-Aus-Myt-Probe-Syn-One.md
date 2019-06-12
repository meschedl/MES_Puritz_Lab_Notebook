---
layout: post
title: Australia Mytilus EecSeq Probe Sythesis Day 1
tags: [ EeqSeq, RNA, cDNA, Mytilus ]
---

### Planning, Pooling, and Concentrating RNA for EecSeq Probe Synthesis
_All steps in are done with [Amy Zyck](https://github.com/amaeliazyck)_

**First step: Aliquoit out 1ug of RNA each from 4 samples from each location and pool together in a locality pool of 4ug**

Doing all locations from the samples sent from Australia as well as a pool for the live Mytilus we collected and extracted [here](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-03-12/Mytilus-Live-RNA-Extraction). We want to have a starting volume of 25μl for the [KAPA Stranded mRNA Seq Kit](https://www.kapabiosystems.com/product-applications/products/next-generation-sequencing-2/rna-library-preparation-2/kapa-stranded-mrna-seq-kits/#accordion-order), so almost all of the pools had to be vacufuged down to either 25μl or less, and then RNase-free water was added to 25μl. These were then re-frozen at -80 because we would not start the library prep until the next day.


| Locality Pool   | Sample | Volume (μl) RNA 1μg | Volume of Pool (μl) | Volume Post-Vacufuge (μl) | Volume (μl) Water to 25μl |
|-----------------|--------|---------------------|---------------------|---------------------------|---------------------------|
| Atlantic (AL)   | A4     | 7.25 | 38.47  | 25      | 0      |
| -         | A5     | 6.33         | -           | -             | -      |
| -        | A7     | 10.63        | -     | -      | -                         |
| -    | 9      | 14.27      | -         | -        | -          |
| France (FR)     | 4385   | 29.15               | 157.59              | 20.8       | 4.2          |
| -               | 4388   | 32.57               | -                   | -        | -        |
| -               | 4395   | 39.68               | -                   | -         | -             |
| -               | 4405   | 56.18               | -                   | -           | -        |
| Montenegro (MN) | 4425   | 21.65               | 136.18              | 20         | 5         |
| -               | 4415   | 16.67               | -                   | -      | -          |
| -               | 4445   | 54.95               | -                   | -        | -       |
| -               | 4452   | 42.92               | -                   | -        | -      |
| Tasmania (TZ)     | 4598 | 10.29 | 35.89 | 25 | 0    |
| -                 | 4599 | 11.36 | -     | -  | -    |
| -                 | 4593 | 3.61  | -     | -  | -    |
| -                 | 4612 | 10    | -     | -  | -    |
| Rhode Island (RI) | 9R   | 5.62  | 20.25 | -  | 4.75 |
| -                 | 10R  | 6.76  | -     | -  | -    |
| -                 | 11R  | 4.48  | -     | -  | -    |
| -                 | 12R  | 3.75  | -     | -  | -    |

**Second step: Make working stock dilution of adapters**

Because we will be using 4000ng of RNA for each library, we needed to make a adapter stock concentration of 1400nM [see kit protocol for details](https://github.com/meschedl/MES_Puritz_Lab_Notebook/blob/master/company-protocols/KAPA-Stranded-mRNA-Seq-TDS-KR0960-v5-17.pdf).

Our annealed adapters are at 40uM, and we want to make a working stock of 60ul, so the calculation is:  
1,400/40,000 * 60 = 2.1μl of adapter stock and 57.9μl of water.  
Created working stocks of SAII and NCO adapters.

**Third step: Make the plan for adapters and indexes for each locality pool**

| Locality Pool | Adapter | Index 1 | Index 2 |
|---------------|---------|---------|---------|
| AL            | SAII    | 501     | 701     |
| FR            | NCO     | 502     | 702     |
| MN            | NCO     | 503     | 703     |
| TZ            | SAII    | 504     | 704     |
| RI            | NCO     | 505     | 705     |
