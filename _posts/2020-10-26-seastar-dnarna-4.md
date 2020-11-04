---
layout: post
title: Troubleshooting DNA/RNA Extraction of Pentagona and Hystera Sea Stars 3
tags: [ RNA, DNA, Pentagona, Hystera, ]
---

# DNA/RNA Extractions on 3 Sea Star Tissue Samples Stored in DNA/RNA Shield, 2 Pentagona and 1 Hystera Only Incubation

### Notes

- Using the [Zymo DNA/RNA Miniprep Plus kit](https://www.zymoresearch.com/collections/quick-dna-rna-kits/products/quick-dna-rna-miniprep-plus-kit)
- Incubated only for 3.5 hours

## Sample Preparation

- Samples:
  - CPBO-003
  - CHSB-011
  - CPDB-008
- Thawed samples on ice bucket
- Prepared forceps, foil, and razor blades
- Cleaned forceps with 10% bleach, DI water, 70% ethanol, and RNaseZap before and between each sample
- Made 1 1.5mL tube per sample with 300ul of DNA/RNA shield in each
- Cut a small piece of tissue for each sample then minced with the razor blade until it was flat and could come apart a little bit and placed in tube with shield
- CPBO-003 tissue piece and minced piece
![1]({{ site.baseurl}}/images/CPBO-003-1.jpeg "1")
![2]({{ site.baseurl}}/images/CPBO-003-2.jpeg "2")
- CHSB-011 tissue piece and minced piece
![3]({{ site.baseurl}}/images/CHSB-011-1.jpeg "3")
![4]({{ site.baseurl}}/images/CHSB-011-2.jpeg "4")
- CPDB-008 tissue piece and minced piece
![5]({{ site.baseurl}}/images/CPDB-008-1.jpeg "5")
![6]({{ site.baseurl}}/images/CPDB-008-2.jpeg "6")
- All tubes pre-incubation:
![7]({{ site.baseurl}}/images/pre-incubate.jpeg "7")
- Added 30ul ProK digestion buffer and 15ul of Proteinase K to each bead tube
- Votexed and spun down tubes
- Placed in thermomixer at 55 degrees C for 3.5 hours shaking at 700rpm
- All tubes post-incubation
![8]({{ site.baseurl}}/images/post-incubate.jpeg "8")
- Used the minifuge to centrifuge and pellet the pieces still in the tube
- Removed ~300ul of liquid supernatant to new 1.5mL tubes

### DNA Extraction

- Added equal volume (300ul) DNA/RNA lysis buffer to each new 1.5mL tube
- Flicked and inverted tubes to mix and spun down
- Warmed 10mM Tris HCl pH 8 and nuclease free water in the thermomixer at 70 degrees C
- Added 700ul of the liquid to yellow spin columns and collection tubes
- Centrifuged 16,000rcf for 30 seconds
- Saved the flow through in new 5mL tubes
- Added the remaining liquid to the yellow spin columns
- Centrifuged 16,000rcf for 30 seconds
- Saved the flow through in the 5mL tubes
- Added 400ul DNA/RNA prep buffer to the yellow spin columns
- Centrifuged 16,000rcf for 30 seconds
- Discarded flow through (Zymo kit waste)
- Added 700ul DNA/RNA wash buffer to the yellow spin columns
- Centrifuged 16,000rcf for 30 seconds
- Discarded flow through (Zymo kit waste)
- Added 400ul DNA/RNA wash buffer to the yellow spin columns
- Centrifuged 16,000rcf for **2 minutes**
- Transferred spin columns to new 1.5mL tubes for each sample labeled as final DNA tubes
- Discarded flow through and collection tubes
- Added 50ul warmed 10mM Tris HCl to the spin columns gently by dripping over the filter
- Incubated at room temp for 5 minutes
- Centrifuged 16,000rcf for 30 seconds
- Added another 50ul warmed 10mM Tris HCl to the spin columns gently by dripping over the filter
- Incubated at room temp for 5 minutes
- Centrifuged 16,000rcf for 30 seconds
- Discarded the spin columns
- Made strip tubes with 7ul of each sample in them for QC
- Kept tubes on ice bucket then stored in -20 degree freezer

### RNA Extraction

- Added equal volume (900ul) 100% ethanol to each 5mL tube
- Vortexed and spun down
- Added 700ul of the liquid to green spin columns and collection tubes
- Centrifuged 16,000rcf for 30 seconds
- Discarded flow through (Zymo kit waste)
- Repeated addition for the remaining liquid (2 times) to the green spin columns
- Centrifuged 16,000rcf for 30 seconds
- Discarded flow through (Zymo kit waste)
-  Added 400ul DNA/RNA wash buffer to the green spin columns
- Centrifuged 16,000rcf for 30 seconds
- Discarded flow through (Zymo kit waste)
- Created the DNase mix:
  - 75ul DNA digestion buffer * 4 = 300ul
  - 5ul DNase I * 4 = 20ul
- Flicked and spun down mix
- Added 80ul DNAse mix to each green spin column filter
- Incubated for 15 minutes at room temp
- Added 400ul DNA/RNA prep buffer to the green spin columns
- Centrifuged 16,000rcf for 30 seconds
- Discarded flow through (Zymo kit waste)
- Added 700ul DNA/RNA wash buffer to the green spin columns
- Centrifuged 16,000rcf for 30 seconds
- Discarded flow through (Zymo kit waste)
- Added 400ul DNA/RNA wash buffer to the green spin columns
- Centrifuged 16,000rcf for **2 minutes**
- Transferred spin columns to new 1.5mL tubes for each sample labeled as final RNA tubes
- Discarded flow through and collection tubes
- Added 50ul warmed nuclease free water to the spin columns gently by dripping over the filter
- Incubated at room temp for 5 minutes
- Centrifuged 16,000rcf for 30 seconds
- Added another 50ul warmed nuclease free water to the spin columns gently by dripping over the filter
- Incubated at room temp for 5 minutes
- Centrifuged 16,000rcf for 30 seconds
- Discarded the spin columns
- Made strip tubes with 5ul of each sample in them for QC
- Kept tubes on ice bucket then stored in -80 degree freezer

### QC

#### Broad Range Qubit for DNA and RNA

- Followed [Qubit protocol](https://github.com/meschedl/PPP-Lab-Resources/blob/master/Protocols/Qubit-Assay-Protocol.md)
- DNA

|Sample|Reading 1 (ng/ul)|Reading 2 (ng/ul)|Average DNA (ng/ul)|
|---|---|---|---|
|Standard 1|186 RFU|-|-|
|Standard 2|21048 RFU|-|-|
|CPBO-003|19.5|19.4|19.45|
|CHSB-011|11.9|11.8|11.85|
|CPDB-008|15.8|15.6|15.7|

- RNA

|Sample|Reading 1 (ng/ul)|Reading 2 (ng/ul)|Average RNA (ng/ul)|
|---|---|---|---|
|Standard 1|397 RFU|-|-|
|Standard 2|8577 RFU|-|-|
|CPBO-003|32.8|32.6|32.7|
|CHSB-011|10.2|10.4|10.3|
|CPDB-008|25.2|25.6|25.4|


#### RNA TapeStation

- Followed [RNA tapestation protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/RNA-TapeStation-Protocol/)
- [TapeStation Report link](https://github.com/meschedl/MES_Puritz_Lab_Notebook/blob/master/tapetstations/2020-10-26%20-%2015.43.14.pdf)

#### Notes: all RNA is very degraded
