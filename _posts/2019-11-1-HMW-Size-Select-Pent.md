---
layout: post
title: Pentagona HMW Size Selection with BluePippin
tags: [ Pentagona, HMW DNA, BluePippin, Size Selection ]
---

# Using the [BluePippin](http://www.sagescience.com/products/bluepippin/) [High Pass Plus Cassette,  >15 kb  DNA size collections](http://store.sagescience.com/s.nl/it.A/id.2093/.f) to further refine our [HMW _pentagona_ DNA](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-10-31/Zymo-HMW-Pent) to above 15,000bp fragments only

### Sample Prep
11/1/19

- Took out electrophoresis buffer, marker, and loading solution from the 4 degree fridge at least 30 minutes before use to get to room temp
- Prepared PCR tubes with 25µl of PG1 extraction in one tube and 25µl of PG2 extraction in another
- Added 5µl of TE buffer to each sample to bring up to 30µl
- Added 10µl of room temp loading solution to each sample and pipetted to mix

### BluePippin Prep
11/1/19

- Updated software to version v6.31/6.40 CD31
- Created a new protocol for this cassette:
  - Cassette type: BPLUS10 15KB HighPass Plus **Marker U1**
  - Selected "range" for lanes 5 and 3
  - Selected reference for lane 4
  - Clicked "apply reference to all lanes"
  - Unclicked range and set reference to off for lanes 2 and 1
  - Set start as 15,000bp and end as 150,000bp so the target was 82,500bp for lanes 5 and 3
  - Saved protocol as MES_15kb_HighPass
- Brought p20, cassette, tips, solutions, and samples up to the GSC
- Calibrated the optics feature
- Unwrapped cassette and looked for problems with the gel: none
- Tipped cassette vertically with elution wells at the top and tapped it to let bubbles release to the top
- Checked amount of buffer in reservoirs: all well full
- Placed in nest and removed seals
- Removed all buffer from elution modules (~80µl) and replaced it with fresh electrophoresis buffer 80µl. _Do this in all elution modules even ones not using_
- Sealed elution modules with sicky provided with the cassettes
- Closed lid and performed continuity test: passed
- Removed 40µl of buffer from the sample wells that were going to be used (5, 4, and 3 only) _note how the sample wells look different in this cassette!!!_
![1]({{ site.baseurl}}/images/cassette.png)
- Added 40µl PG1 to well 5
- Added 40µl marker U1 to well 4
- Added 40µl PG2 to well 3
- Closed lid and pressed start 2:51pm
- Program ran until idle 5:22pm
- Set timer for 45 min to let all sample elute and waited to remove until after that
- After 45 min, removed sticker and saved all the liquid in elution modules 5 and 3 (80µl each) in separate tubes
- Filled elution modules 5 and 3 with 80µl 0.1% Tween and waited 1 minute, then removed and saved those liquids as well
- Ran D5000 tapestation on the elution module liquid and placed all samples in the 4 degree fridge for storage
![2]({{ site.baseurl}}/images/highpass1.png)
![3]({{ site.baseurl}}/images/highpass2.png)

### 0.45X Cleanup of Size Selected Samples
11/4/19 and 11/5/19

- Made fresh 80% EtOH before starting
- Took KAPA Pure Beads out of fridge about 30 minutes before they were needed
- Used pipettes to determine how much volume of sample out of the BluePippin there was:
  - PG1: 81µl so .45X is 36.45µl of KAPA Pure Beads
  - PG2: 80µl so .45X is 36µl of KAPA Pure Beads
- Added the above amount of beads to each sample very gently then stirred each sample with the pipette tip for about 10 seconds each
- Placed tubes on shaker for 20 minutes at room temp
- Then placed the tubes on the magnet rack and waited 10 minutes
- Removed the clear supernatant and saved in separate tubes just in case of loss of sample
- Added 200µl of fresh 80% EtOH to each tube gently then waited 30 seconds
- Removed and discarded the supernatant
- Added 200µl of fresh 80% EtOH to each tube gently then waited 30 seconds
- Removed and discarded the supernatant
- Spun sample tubes briefly in tabletop minifuge and placed back on the magnet rack
- Used p20 to get the last liquid out of the tube, just a few µl
- Let tubes sit open for ~1 minute
- Removed tubes from rack and added 50µl of nuclease free water to each tube
- Flicked tubes until the pellets resuspended and then briefly spun down because liquid was all on the lids
- Placed tubes closed on sample rack still at room temp for 20 minutes
- After then placed on shaker at room temp for afternoon and overnight
- The next morning, spun down tubes briefly because some evaporation, also the beads had settled to the bottom mostly
- Placed tubes on the magnet rack for 10 minutes
- Removed the clear supernatant and placed into new labeled sample tubes

**Broad Range Qubit of top, middle, and bottom of sample tube**  
Flipped tube end over end to try to mix sample before taking 1µl to Qubit

|Standard 1|Standard 2|PG1 top|PG1 middle|PG1 bottom|PG2 top|PG2 middle|PG2 bottom|
|----|----|-----|-----|----|----|----|-----|
|185|20697|5.48|5.38|5.70|2.76|2.68|2.72|
|-|-|5.28|5.26|5.60|2.64|2.56|2.56|


Not a lot left so we decided to size select the rest of the extraction

**11/5/19 BluePippin HighPass >15kb Size Selection**

- Let all reagents come to room temp
- Took the rest of each extraction, about 20µl each, and brought up to 30µl with TE buffer
- Added 10µl loading solution to each sample and pipetted to mix
- Followed exact steps as above section for running the BluePippin, again the run took almost exactly 2.5 hours to complete and the samples sat in the cassette an extra 45 minutes after the run was finished to facilitate any final elution
- Samples were saved from the elution modules and tween washes were also taken of the elution modules
- Samples were inverted a few times then run with a Broad Range Qubit assay and a D5000 TapeStation:

|Standard 1| Standard 2|PG1 A|PG2 A|
|---|---|---|---|
|181|19675|2.26|2.24|
|-|-|2.38|3.22|

![4]({{ site.baseurl}}/images/highpass3.png)
![5]({{ site.baseurl}}/images/highpass4.png)
