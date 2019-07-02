---
layout: post
title: Australia Mytilus EecSeq Probe Synthesis Day 5
tags: [ EeqSeq, RNA, cDNA, Mytilus ]
---

## DSN Normalization

_Continuing with [Amy Zyck](https://github.com/amaeliazyck)_

We want to do 2 normalizations to maximize how many probes we make. Each normalization is for 500ng, and in a total volume of 13.5μl. We do not have libraries at a concentration high enough for that, so we want to pool a little over a 1μg of all the libraries, do a 1.8X bead cleanup on that, Qubit, then dilute to 13.5μl if it is not at that volume.

We determined to pool 228ng of each locality pool library because the RI library has a really low quant, and that is all 19μl of that library. We keep the amount the same across all libraries because we do not want over representation of one locality pool. This would give us a total of 1140ng. Then we had to determine the volume to elute in that would allow for 1μl to go to the Qubit, and then the rest to be split between the two normalizations, be 500ng each, and be under 13.5μl. We guessed that an elution volume of 25μl 10mM Tris HCl pH 8 would work. If we lost no DNA (unrealistic) the concentration would be 45.6ng/μl. That would mean that only 10.9μl would be needed for 500ng and there would be enough for the Qubit. And there is some room for error here.

1. Pooled 228ng of each library together
  - AL: 9.01μl
  - FR: 10.56μl
  - MN: 7.97μl
  - TZ: 6.30μl
  - RI: 19μl
2. Did a 1.8X bead clean up. Total volume of the pooled libraries was 52.84μl, so 95.11μl of room temp KAPA pure beads were added and pipetted to mix.
3. Tube was placed on the shaker for 15 minutes
4. Made fresh 80% EtOH
5. Placed tube on the magnet plate and removed the supernatant when it was clear
6. Added 200μl EtOH carefully
7. Removed 180μl EtOH carefully
8. Added 150μl EtOH carefully
9. Removed all supernatant, using the smallest pipette tip to remove any droplets present
10. Barely let the beads dry (less than 30 seconds) and eluted the beads in 25μl 10mM Tris HCl pH 8
11. Put tube on the shaker for 5 minutes
12. Placed tube back on to the magnet plate and removed 25μl of the clear supernatant into a new tube.

BR Qubit  
636.8μl BR Buffer  
3.2μl BR Quant-It reagent
(Followed [this](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-03-02/Qubit-Protocol) protocol)
  - S1: 195 RFU
  - S2: 20102 RFU
  - Pooled cleaned libs: 41.2ng/μl

For 500ng it is 12.14μl
13. Made 2 new PCR tubes with 12.14μl pooled and cleaned libraries each and added 1.36μl 10mM Tris HCl pH 8 to get to 13.5μl
14. Made 4X hybridization buffer:
  - 200μl 1M HEPES Buffer
  - 400μl 5M NaCl
  - 400μl nuclease-free water
15. Added 4.5μl 4X hybridization buffer to each PCR tube
16. Pipetted entire volume (18μl) up and down 10 times for both tubes
17. Transferred entire volume of each tube into new PCR tubes
18. Placed in thermocycler DSN program: 98C 2 min, 68C 5 hours
19. With about 30 minutes left, prepared the 2X DSN master buffer:
  - 2 new PCR tubes
  - 16μl nuclease-free water
  - 4μl 10X master buffer
20. Put 2X master buffer in a second thermocycler at 68C hold
21. Waited at least 10 minutes for the master buffer to be solidly at 68 degrees
22. One PCR tube at a time:
  - Opened the 2nd thermocycler and removed the full 20μl of 2X DSN master buffer
  - Closed the 2nd thermocycler and opened the 1st thermocycler
  - Added the 20μl to the 1st probe tube
  - Used a p200 at 35μl to pipette the liquid in the tube up and down 10 times, not removing from the thermocycler, took a little extra pipetting to remove bubbles
  - Repeated those steps for the second master buffer and probe tube
23. Incubated tubes in the thermocycler at 68C for 10 minutes
24. One probe tube at a time and closing the thermocycler inbetween additions, added 2μl of DSN enzyme, then used a p200 at 40μl to pipette the liquid up and down 10 times inside the the thermocycler, again doing a bit more to remedy bubbles
25. Repeated above step for the second probe tube
26. Incubated at 68C for 25 minutes
27. Added 40μl 2X DSN stop solution to each tube, pipetted to mix at least 10 times and placed on ice
28. Placed in the -20 degree freezer for overnight
