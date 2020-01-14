---
layout: post
title: Extracting DNA from Pentagona Sea Star with the Circulomics Nanobind HMW Kit and Using Short Read Eliminator XL
tags: [ Pentagona, HMW DNA, Nanobind, Extraction ]
---

# Using [Nanobind Big DNA Kit with Alpha Version Reagents](https://www.circulomics.com/store/Nanobind-Tissue-Big-DNA-Kit-p129187130) on another Pentagona tissue sample preserved in DNA/RNA Shield, followed mostly the recommendations of the [Snail Note](https://15a13b02-7dac-4315-baa5-b3ced1ea969d.filesusr.com/ugd/5518db_49ee69b3459c44abab7f7287e8da499e.pdf?index=true). Then using the [Short Read Eliminator XL Kit](https://www.circulomics.com/store/Short-Read-Eliminator-XL-p138401730) on the DNA

### Sample Prep - 20200113

- Placed dounce homogenizer, buffer CIB (same as CT), and one tube of P6 sample on ice
- While waiting for sample to thaw set the centrifuge for 4 degrees C and let run for 7 minutes to bring the temp down
- Cut two pieces of foil and sterilized forceps, got a scalpel and new blade
- Took tissue piece out of tube when thawed and cut in half on one foil sheet, minced one half with scalpel blade as much as obvious ossicles out allow
- Rest of tissue was returned to sample tube and placed back in -20 freezer
- Weighed fresh foil sheet empty and with minced tissue piece:
  - Before: 0.2598g
  - With tissue: 0.3105g
  - Tissue weight: 0.051g or 51mg
- Goal was 60mg so this was deemed close enough
- Minced tissue was placed in the chilled dounce and 750µl of  cold buffer CIB was added to the dounce
- The tissue was homogenized with the tight pestle 20 times (snail note says 15, but it looked like it needed a little more). The ossicles did not homogenize and stayed as a smushed pancake at the bottom of the dounce. This didn't cause a problem as the tissue still moved and was broken up
- Transferred liquid and as much of the bubbles as possible to a 2mL protein lobind tube
- Centrifuged at 6000rcf for 5 minutes at 4 degrees C
- Removed supernatant without disturbing the pellet (pellet was orange) _saved supernatant in case something went wrong_
- Added 1mL of cold buffer CIB to the tube and pulse-vortexed 10 times
- Centrifuged at 6000rcf for 5 minutes at 4 degrees C
- Removed supernatant without disturbing the pellet _saved supernatant again in case something went wrong_
- Pulse-vortexed the pellet 2 times
- Added 20µl of proteinase K to the pellet
- Added 150µl of buffer CLE3 and pipette-mixed 10 times with a wide bore pipette tip
- Put tube in Thermomixer 55 degrees C 900rpm shaking for 30 minutes
- After 30 minutes checked homogenization: liquid was very opaque white but there were no visible chunks or pieces so I thought it was good to go
- Spun down in minifuge to remove liquid from cap
- Added 20µl RNase A
- Incubated in Thermomixer 55 degrees C 900rpm shaking for 30 minutes

### Extraction

- Spun down in minifuge to remove liquid from cap
- Added 60µl buffer SB and pulse-vortexed 5 times _sample became very white_
- Centrifuged 10,000rcf for 5 minutes at room temp
- Transferred ~300µl supernatant to a new 1.5mL lobind protein tube _there was a large white pellet in the tube_
- Added 50µl buffer BL3 to tube with supernatant and inverted 10 times to mix _liquid became cloudy with mixing_
- Spun on minifuge 2 seconds
- Added 1 nanobind disk
- Added 350µl of isopropanol
- Inverted to mix 10 times _became clear after mixing_
- Placed on orbital mixer/shaker because it's the only thing we have that goes 20rpm. 15 minutes on mixer at room temp
- Placed tube on magnet using method:
![1]({{ site.baseurl}}/images/magmethod.png)
- Carefully removed and discarded supernatant
- While on magnet added 500µl CW1
- Removed tube from magnet and inverted 4 times
- Placed tube back on magnet using method
- Removed and discarded supernatant
- While on magnet added 500µl CW1
- Removed tube from magnet and inverted 4 times
- Placed tube back on magnet using method
- Removed and discarded supernatant
- While on magnet added 500µl CW2
- Removed tube from magnet and inverted 4 times
- Placed tube back on magnet using method
- Removed and discarded supernatant
- While on magnet added 500µl CW2
- Removed tube from magnet and inverted 4 times
- Placed tube back on magnet using method
- Removed and discarded supernatant
- Pipetted out residual liquid from the tube cap
- Spun down tube in minifuge
- Placed on magnet in normal way
- Removed and discarded any residual liquid
- Added 75µl buffer EB directly to the disk _disk ended up being fully submerged in the buffer_
- Incubated at room temp for 30 minutes
- Used wide bore tip to transfer liquid to a new 1.5mL DNA lo bind tube
- Spun down tube with disk in minifuge and pipetted up residual elutate with regular pipette tip
- Spun down tube with disk again but there was no residual liquid
- Pipetted 5 times with normal p200 pipette tip
- Left overnight at RT to let DNA solubilize
- In the morning: pipetted 5 times with normal p200 tip

**BR DNA Qubit**

- following [protocol](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-03-02/Qubit-Protocol)
- Quantified top, middle, and bottom of liquid just in case the DNA wasn't evenly distributed

|standard 1|standard 2|top|middle|bottom|average|
|---|---|---|---|---|---|
|193 RFU|21165 RFU|105ng/μl|103ng/μl|102ng/μl|**103.3ng/μl**|

**Genomic DNA TapeStation**

- Visualize DNA size with genomic DNA tapestation [protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/DNA-Tapestation/)
- [Link](https://drive.google.com/open?id=1h3Xl0JqkNz0BrQ3ZsJmRSlHZLZqdWeAG) to full results

![2]({{ site.baseurl}}/images/prent-nano.png)


## Short Read Eliminator XL Kit - 20200114

- Transferred 60µl of sample from previous extraction to a new DNA Lo bind 1.5mL tube
- Added 60µl buffer SRE XL with a wide bore tip and pipetted to mix ~7 times then tapped a bit because it didn't look mixed
- Placed in centrifuge with tube hinge facing the outside
- Centrifuged for 30 minutes at 10,000rcf at room temp, using the non-temp controlled centrifuge
- Made fresh 80% EtOH and warmed elution buffer to 50 degrees C
- After centrifugation, removed supernatant without disturbing the pellet _there was a pellet, very hard to see, looked like a small squiggle at the bottom of the tube_
- Added 200µl 80% EtOH to the side of the tube without touching the pellet
- Centrifuged for 2 minutes at 10,000rcf RT
- Removed wash without disturbing the pellet
- Added 200µl 80% EtOH to the side of the tube without touching the pellet
- Centrifuged for 2 minutes at 10,000rcf RT
- Removed wash and any residual droplets
- Added 50µl warmed buffer EB and placed tube in thermomixer at 50 degrees C for 30 minutes
- Tapped tube a few times to redistributed DNA

**BR DNA Qubit**

- following [protocol](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-03-02/Qubit-Protocol)
- Quantified top, middle, and bottom of liquid just in case the DNA wasn't evenly distributed

|standard 1|standard 2|top|middle|bottom|average|
|---|---|---|---|---|---|
|200 RFU|21694 RFU|42.6ng/μl|59.8ng/μl|70.8ng/μl|**57.26ng/μl**|

**Genomic DNA TapeStation**

- Visualize DNA size with genomic DNA tapestation [protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/DNA-Tapestation/)
- [Link](https://drive.google.com/open?id=1OTvYT1H6-kd1DdZR1YDMTIAnSK_hgI9Z) to full results

![2]({{ site.baseurl}}/images/pent-nano-SRE.png)

Combined of both pre and post SRE

![3]({{ site.baseurl}}/images/pent-nano-SRE-comp.png)
