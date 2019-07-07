---
layout: post
title: Australia Mytilus EecSeq Probe Synthesis Day 6
tags: [ EeqSeq, RNA, cDNA, Mytilus ]
---

## Enrichment of DSN Treated Libraries

_Continuing with [Amy Zyck](https://github.com/amaeliazyck) and also [Jacob Green](https://github.com/madmolecularman)_

1. Take tubes out of the freezer and thaw
2. Warm KAPA pure beads to room temp and make new 80% EtOH
3. Added 128μl KAPA pure beads to each of the two tubes and pipetted to mix
4. Placed on shaker for 15 minutes
5. Placed tubes on magnet plate and removed the supernatant when clear
6. Added 200μl 80% EtOH to each tube carefully
7. Removed ~180μl supernatant from each tube carefully
8. Added 200μl 80% EtOH to each tube carefully
9. Removed ALL supernatant from each tube and used p20 tips to remove any EtOH droplets
10. Resuspended beads in 25μl 10mM Tris HCl pH 8
11. Put tubes on shaker for 5 minutes
12. Placed tubes on magnet stand and removed 25μl of clear supernatant into new tubes
13. Performed HS Qubit on DSN treated libraries (Followed [this](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-03-02/Qubit-Protocol) protocol)
  - S1: 64 RFU
  - S2: 25850 RFU
  - Tube 1: 0.718ng/μl
  - Tube 2: 0.762ng/μl

**PCR Enrichment of DSN Treated Libraries**
14. Master mix for PCR:
  - 25μl 2X KAPA HiFi Hot Start ready mix * 2.2 = 55μl
  - 5μl 10X KAPA library amplification primer mix * 2.2 = 11μl
15. Made 2 new tubes for the PCR
16. Added 30μl master mix each to the new tubes
17. Added 20μl of DSN treated library pools to the appropriate tube for a total volume of 50μl
18. Votexed to mix and spun down
19. Placed in the thermocycler DSN PCR program **14** cycles
20. Took KAPA beads out of the fridge to warm to room temp
21. Afterwards, spun down and a 1.6X bead clean up
22. Added 80μl KAPA pure beads to each tube and pipetted to mix
23. Placed on shaker for 15 minutes
24. Placed tubes on magnet plate and removed the supernatant when clear
25. Added 200μl 80% EtOH to each tube carefully
26. Removed ~180μl supernatant from each tube carefully
27. Added 200μl 80% EtOH to each tube carefully
28. Removed ALL supernatant from each tube and used p20 tips to remove any EtOH droplets
29. Resuspended beads in 22μl 10mM Tris HCl pH 8
30. Put tubes on shaker for 5 minutes
31. Placed tubes on magnet stand and removed 22μl of clear supernatant into new tubes
32. Performed BR Qubit on DSN treated libraries (Followed [this](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-03-02/Qubit-Protocol) protocol)
  - S1: 197 RFU
  - S2: 21088 RFU
  - Tube 1: 2.5ng/μl
  - Tube 2: 7.2ng/μl
34. Ran D5000 TapeStation on the two post DSN normalized samples  
![one]({{ site.baseurl}}/images/normalized-1-1.png "one")
![two]({{ site.baseurl}}/images/normalized-1-2.png "two")  
It's really hard to tell, especially in the first sample, if there is any primer or left over digested adapter in the traces because the amount is so low. We did a second PCR of the already PCR'd samples to check
35. Took 2μl from each of the already PCR'd samples and added 18μl of 10mM Tris HCl pH 8 to each to get to 20μl.
36. Made the same master mix as above, 55μl KAPA ready mix and 11μl of KAPA primer mix
37. 30μl master mix into the new tubes with the diluted 2μl of PCR'd samples
38. Put in the thermocycler same program DSN PCR 14 cycles
39. Performed BR Qubit (Followed [this](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-03-02/Qubit-Protocol) protocol)
  - S1: 193 RFU
  - S2: 19922 RFU
  - Tube 1: 223ng/μl
  - Tube 2: 252ng/μl
40. Ran the TapeStation (D5000) to check for smaller fragments now that the concentration is so high
![one]({{ site.baseurl}}/images/normalized-2-1.png "one")
![two]({{ site.baseurl}}/images/normalized-2-2.png "two")
The peaks above ~300bp are evidence of overamplification and secondary structures of DNA in the reactions, but there is no amplification of adapter or primers in these samples which is the important part.
41. To proceed, we did another 8 cycle amplification from the original post DSN PCR'd samples (see step 32). To avoid overamplification, three reactions with 5μl each per sample were made for a total of 6 reactions
42. Made master mix for the PCR:
  - 12.5μl KAPA ready mix * 6.2 = 77.5μl
  - 2.5μl KAPA primer mix * 6.2 = 15.5μl
43. Added 5μl of sample 1 DNA to 3 new PCR tubes, and added 5μl of sample 2 DNA to 3 new PCR tubes
44. Added 5μl of 10mM Tris HCl to each of those to dilute to 10μl
45. Added 15μl of the amplification master mix to each tube for a total reaction volume of 25μl
46. Vortexted, spun down, and placed in the thermocycler DSN PCR program **8 cycles**
47. Took KAPA pure beads out of the 4 degree to warm to room temp
48. After the PCR was finished, pooled the 3 tubes from each set together for 2 tubes with 75μl
49. Performed a 1.6X cleanup by adding 120μl KAPA beads and pipetting to mix
50. Placed on shaker for 15 minutes
51. Placed tubes on magnet plate and removed the supernatant when clear
52. Added 200μl 80% EtOH to each tube carefully
53. Removed ~180μl supernatant from each tube carefully
54. Added 200μl 80% EtOH to each tube carefully
55. Removed ALL supernatant from each tube and used p20 tips to remove any EtOH droplets
56. Resuspended beads in 22μl 10mM Tris HCl pH 8
57. Put tubes on shaker for 5 minutes
58. Placed tubes on magnet stand and removed 22μl of clear supernatant into new tubes
59. Performed BR Qubit (Followed [this](https://meschedl.github.io/MES_Puritz_Lab_Notebook/2019-03-02/Qubit-Protocol) protocol)
  - S1: 191 RFU
  - S2: 20665 RFU
  - Tube 1: 138ng/μl
  - Tube 2: 196ng/μl
60. Ran the TapeStation (D5000) to check for overamplification and the right distribution
![one]({{ site.baseurl}}/images/normalized-3-1.png "one")
![two]({{ site.baseurl}}/images/normalized-3-2.png "two")
There is a lot more DNA in these and much less overamplification, success!   
Tubes placed in the fridge overnight
