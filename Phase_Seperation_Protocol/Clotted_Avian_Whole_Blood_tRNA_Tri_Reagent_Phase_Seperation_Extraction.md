# Clotted Avian Whole Blood total RNA extraction Protocol
Jonathan Dain
2026-07-06

## Purpose:

The purpose of this protocol is to extract total RNA (tRNA) from
nucleated avian whole blood samples that have been collected (preserved)
in DNA/RNA shield and stored at -80ºC. The eluted tRNA will be used in
downstream applications including library prep, sequencing, and gene
expression studies.

> 💡 **Note:** This protocol has been improved to handle samples in
> which there is a considerable blood clot.

This protocol has been adapted from multiple sources. The base of this
protocol is the Zymo Direct-zol-96 MagBead RNA kit. Their protocol can
be found
[here](https://files.zymoresearch.com/protocols/_r2100_r2101_r2102_r2103_r2104_r2105_direct-zol-96_magbead_rna.pdf).
It was then modified using information in Dr. Johanna Harvey’s RNA
extraction that can be found
[here](https://github.com/JAHarvey/RNA-Blood-preservation-extraction).
Finally, this protocol has been adapted to allow the use of a Kingfisher
Flex ‘benchtop’ robot. The automation script can be found
[here](https://github.com/Jonathan-Dain-42/RNA-Blood-Phenol-Extraction/Phase_Seperation_Protocol/Avian_Whole_Blood_tRNA_Tri_Reagemt_Phase_Seperation_Extraction.html)

The printable version of this protocol can be found
[here](https://htmlpreview.github.io/?https://github.com/Jonathan-Dain-42/RNA-Blood-Phenol-Extraction/blob/main/Phase_Seperation_Protocol/Clotted_Avian_Whole_Blood_tRNA_Tri_Reagent_Phase_Seperation_Extraction.html).

## Safety Information:

> ⚠️ **Warning:** TRI-Reagent contains the compound
> [phenol](https://files.zymoresearch.com/sds/_r2050-1-50_tri_reagent_us.pdf?_gl=1*14j31np*_gcl_au*MTcwNTM4ODE5Ni4xNzY4OTI1NDQ4LjIzODk3MTg2OC4xNzY4OTMxNjk0LjE3Njg5MzE4Njc.)
> which is extremely toxic!! Therefore the parts of this protocol that
> utilize TRI-reagent needs to be done inside of a active fume hood. In
> addition the waste produced during this protocol needs to be disposed
> of in the proper waste receptical.

## Equipment Checklist:

- 1 x MagBind Tube Stand (Green)
- 1 x Pipette-10 + Tips
- 1 x Pipette-200 + Tips
- 1 x Pipette-1000 + Tips
- 1 x Centrifuge (i.e. “Jake” placed in the 4ºC walk-in freezer)
- Autoclaved 3mm steal beads (2 per sample)
- Tomy Micro Tube Mixer MT-360 “Tony”
- Paint shaker from the Moyers lab in 3206
- Green Bucket with Ice to keep samples cold

| Reagents | x 1 sample | x 12 samples | x 24 samples |
|:---|:--:|:--:|:--:|
| Tri-Reagent | 1000 uL | 12 mL | 24 mL |
| Mag Beads | 20 uL | 240 uL | 480 uL |
| DNA/RNA Wash 1 Buffer | 500 uL | 6 mL | 12 mL |
| DNA/RNA Wash 2 Buffer | 500 uL | 6 mL | 12 mL |
| EtOH (Two Plates) | 500 uL x 2 | 6 mL x 2 | 12 mL x 2 |
| DNase/RNase Free Water (Aliquot) | 100 uL | 1.2 mL | 2.4 mL |
| 1-Bromo-3-chloropropane @ 4ºC | 100 uL | 1.2 mL | 2.4 mL |
| DNA/RNA Shield | 200 uL (as needed) | 2.4 mL | 4.8 mL |
| DNase 1 (Reconstituted) | 45uL | 540uL | 1080uL |
| DNA Digestion Buffer | 5uL | 60uL | 120uL |

## Pre-Extraction Checklist:

- [ ] Do you have enough 3 mm beads for the number of samples you have?

- [ ] Are the scissors and forceps autoclaved and RNase zapped?

- [ ] Are the centrifuge (“Jake”) and tube mixer (“Tony”) in the 4ºC
  walk-in fridge? (This should be done at least the day prior)

## Step Zero: Buffer Preparation and Extraction Map

1.  Using your laptop or lab computer navigate to the
    VirusPlusLab/Screening/Blood_RNA_Seq/
2.  Fill out the
    [template](https://liveumb-my.sharepoint.com/:x:/r/personal/nichola_hill_umb_edu/Documents/VirusPlusLab/Screening/Blood_RNA_Seq/Raw_sample_TEMPLATE_UMB.xlsx?d=wc5a8e2974b524b30bbd46593014086eb&csf=1&web=1&e=rDQWN3)
    with the sample vial ID’s and save with the extraction date
    (YYYY-MM-DD).
3.  Print out the extraction template and the current extraction
    [protocol](https://github.com/Jonathan-Dain-42/RNA-Blood-Phenol-Extraction/blob/main/RNA-Blood-Phenol-Extraction-Protocol.mkd) -
    if not done already - for use during the extraction.
4.  If not done already: Add 20 ml (R2100, R2101) or 80 ml (R2102,
    R2103) of isopropanol to the MagBead DNA/RNA Wash 1 concentrate and
    mix well.
5.  If not done already: Add 30 ml (R2100, R2101) or 120 ml (R2102,
    R2103) of isopropanol to the MagBead DNA/RNA Wash 2 concentrate and
    mix well.
6.  If not done already: Reconstitute DNase 1 (E1009-A, 250 U) with
    2.25mL Nuclease free water. Determine aliquot size and store as
    frozen aliquots.
7.  If not done already: Prepare DNase 1 Reaction Mix by adding 45uL
    DNase 1 (reconstituted) and 5uL DNA Digestion Buffer in a nuclease
    free tube. **Scale up proportionally for more samples.** Place on
    ice until ready to use.

- [ ] Buffers prepared prior to this. Initials
  here:\_\_\_\_\_\_\_\_\_\_\_

## Step One: Sample Preparation

> 🦆 🧪 Note: This protocol is designed for use with **avian whole
> blood** samples stored in **DNA/RNA Shield**.

1.  Turn on biosafety cabinet (BSC) in 3204 and let blower “run” for 15
    minutes. Wipe down inside of BSC with quartricide and RNase Zap.
    Additionally wipe down grey counter-tops with quartricide and
    outside of Kingfisher robot with both quatricide and RNase Zap.

2.  Turn the bench-top Kingfisher Flex robot on.

3.  Run a maintenance check of the Kingfisher robot. Use ‘→’ arrow to
    navigate to maintenance tab (i.e. the spanner icon), scroll down to
    maintenance checks (spanner & list icon). Select “Check_96dw_tips”
    program and start. Load the tip comb and ‘Tip Pickup’ plate.

4.  Once the maintenance check is done. Start the tri-reagent KF
    protocol. Use the ‘→’ to navigate to the RNA tab, select
    “**Avian_Blood_TriZol_20260706**” and press start.

5.  Wipe down fume hood area with quatricide and RNase Zap.

6.  In the fume hood label a new autoclaved 2mL eppendorf tube per
    sample. Use a P1000 pipette with P1000 tips to pre-fill each tube
    with 1000uL of Tri-reagent and add 1 x 3mm steel bead.

7.  Aliquot out enough 1-Bromo-3-chloropropane for the extraction (i.e.
    100uL per sample + 50uL for pipetting error) into a autoclaved 5mL
    tube. Place aliquot in the -20ºC freezer.

8.  Pull samples to extract out of the -80ºC freezer and begin thawing
    them on ice in the green ice bucket in fume hood.

9.  When samples are thawed (or mostly thawed depending on the clot
    size) use a fresh set of cleaned forceps and scissors to cut ~200uL
    of the clot and place into the pre-filled Tri-reagent tube.

10. Immediately vortex for 30 seconds then place tube back on ice.

11. Repeat steps 7-8 for the remaining samples.

12. Once clot samples are in the tubes, parafilm the tubes and place
    them on the Tomy Tube mixer (“Tony”) in the 4ºC walk in fridge to
    incubate for 30 minutes. The mixing speed should be set to ~8 on the
    mixer.

13. While the samples are incubating go back to the BSC in 3204 and
    label 7 x Kingfisher 96-deep well plates in the following order:
    Samples, DNA/RNA Wash 1, DNA/RNA Wash 2, Ethanol Wash 1, Ethanol
    Wash 2, DNase, Elution.

14. Add the following reagents to each well, in each plate, in order.

15. Add *500uL* MagBead DNA/RNA Wash 1 to each well in the DNA/RNA Wash
    1 plate.

16. Add *500uL* MagBead DNA/RNA Wash 2 to each well in the DNA/RNA Wash
    2 plate.

17. Add *500uL* Ethanol (96-100%) into ethanol wash plate 1 and 2.

18. Add 50uL of DNase 1 Reaction Mix to each well on the DNase plate.

19. Add *100uL* DNase/RNase free water to each well in the elution
    plate.

20. Load the places (minus the sample plate) onto the robot.

21. After the incubation place the samples into the labeled orange tube
    rack with additional empty tubes for balance/force distribution.
    Take this tube rack to the paint shaker in 3206 and homogenize the
    samples. **Specifically place the samples in the machine for 3
    rounds of 2 minutes each with a 1 minute chill on ice (green bucket)
    between them. Rotate the tube rack 180º between rounds.**

## Step Two: Phase Seperation

1.  Retrieve 1-Bromo-3-chloropropane aliquote from freezer. Add *100μl*
    cold 1-Bromo-3-chloropropane to each sample, shake vigorously for 20
    seconds, then incubate at room temperature 10 minutes.
2.  In the 4ºC walk in centrifuge the samples for 30-60 minutes at
    12,000 x g (or max speed).
3.  Check phase separation: 50-60% of the volume should be clear aqueous
    phase. If separation is poor, add an additional 100 μl
    1-Bromo-3-chloropropane and repeat shake-incubate-spin step.
    Centrifugation separates the mixture into 3 phases: a colorless
    upper aqueous phase containing total RNA, an interphase containing
    DNA, and the red organic phase containing proteins.
4.  Carefully collect up to 400 μl of the aqueous phase, making sure not
    to disturb interphase or lower organic phase, and place in **sample
    plate** taking care to place sample into correct well of sample
    plate. Discared the interphase and lower organic phase. *Note this
    must be discarded in the proper waste receptical.*

> 💡 Here is a visual example of [Phase
> Seperation](https://cdn.shopify.com/s/files/1/0803/9419/1166/files/1_6905ba21-b3eb-4a34-9355-94e0bc796bac_1024x1024.jpg?v=1751352495)

## Step Three: RNA Purification

1.  Add equal volume (~400uL) of ethanol (95-100%) to recovered aqueous
    phase in each well, pipette mix twice.
2.  Add *20uL* MagBinding Beads to each well of the sample plate. (Note
    these settle quickly, vortex beads between every 3 samples).
3.  Load sample plate onto Kingfisher robot in room 3204.

> 🛠️ **The rest of this protocol will be performed by the benchtop
> Kingfisher Flex robot in room 3204 using a custom script mentioned
> above. Buffers are already dispensed into deep well plates the robot
> is manually moving the beads to accomplish the below steps. Step 9 and
> 10 <u>require</u> manual input from user.**

4.  Mix well for 10 minutes then pellet the beads, and discard the
    cleared supernatant.
5.  Add *500uL* MagBead DNA/RNA Wash 1 and mix well. Pellet the beads,
    and again discard the supernatant.
6.  Add *500uL* MagBead DNA/RNA Wash 2 and mix well. Pellet the beads,
    and again discard the supernatant.
7.  Add *500uL* ethanol (96-100%) and mix well. Pellet the beads, and
    again discard the supernatant.
8.  **Repeat Step 7 of RNA Purification.**
9.  Add *50uL* DNase 1 Reaction Mix and mix gently for 10 minutes.
    **Note: The machine will pause after this step for manual input here
    for step 10.**
10. Manually add 500uL RNA Prep Buffer and mix well for 10 minutes.
    **Click Resume on robot.** Pellet the beads and discard the
    supernatant.
11. Repeat steps 7-8.
12. Dry the beads for 10 minutes or until fully dry.
13. Add *100uL* of DNase/RNase-Free Water and mix well for 5 minutes.
14. Elute RNA into 100uL DNase/RNase free water and remove beads.
15. **Off of the robot**, manually aliquot the eluted RNA into a labeled
    0.5mL eppendorf tubes.
16. Aliquot 12.5 ul of RNA for quantitation into strip tubes. Use 2 μl
    for Qubit, 8 μl for Bioanalyzer, and 2 ul for Nanodrop, with the
    remaining 0.5 μl to account for pipetting error. Store RNA in -80°C.
17. Place eluted RNA into -80ºC for storage until further
    processing/sequencing.

## Cleanup and Decontamination

1.  Dispose of all reagents that came in contact with TRI-Reagent (tips,
    tubes, aqueous waste, etc.) into the label waste container.
2.  Close and seal all open reagents and return to proper storage
    locations/temperatures.
3.  Wipe down area with ethanol and RNase Zap.
4.  Remove “Jake” and “Tony” from 4ºC walk-in freezer and place back on
    lab bench in 3200.
5.  Wipe down BSC, grey counters, and Kingfisher robot with quatricide.
6.  Let the BSC blower blow for an additional 15-minutes then turn off
    BSC.
7.  Make note of any changes to the protocol that need to be made and
    any reagents that need to be ordered.
