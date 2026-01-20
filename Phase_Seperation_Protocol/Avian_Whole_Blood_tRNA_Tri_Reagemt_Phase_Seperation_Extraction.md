# Tri-Reagent Avian Whole Blood total RNA extraction Protocol
Jonathan Dain
2026-01-20

## Purpose:

The purpose of this protocol is to extract total RNA from nucleated
avian whole blood samples that have been collected (preserved) in
DNA/RNA shield and stored at -80ºC. The eluted tRNA will be used in
downstream applications including library prep, sequencing, and gene
expression studies.

This protocol has been adapted from multiple sources. The base of this
protocol is the Zymo Direct-zol-96 MagBead RNA kit. Their protocol can
be found
[here](https://files.zymoresearch.com/protocols/_r2100_r2101_r2102_r2103_r2104_r2105_direct-zol-96_magbead_rna.pdf).
It was then modified using information in Johanna Harvey’s RNA
extraction that can be found
[here](https://github.com/JAHarvey/RNA-Blood-preservation-extraction).
Finally, this protocol has been adapted to allow the use of a Kingfisher
Flex benchtop robot. The automation script can be found
[here](https://github.com/Jonathan-Dain-42/RNA-Blood-Phenol-Extraction/Phase_Seperation_Protocol/Avian_Whole_Blood_tRNA_Tri_Reagemt_Phase_Seperation_Extraction.html)

The printable version of this protocol can be found
[here](https://github.com/Jonathan-Dain-42/RNA-Blood-Phenol-Extraction/blob/main/Phase_Seperation_Protocol/Avian_Whole_Blood_tRNA_Tri_Reagemt_Phase_Seperation_Extraction.html).

## Before Starting:

### Safety Information:

> ⚠️ **Warning:** TRI-Reagent contains the compound
> [phenol](https://files.zymoresearch.com/sds/_r2050-1-50_tri_reagent_us.pdf?_gl=1*14j31np*_gcl_au*MTcwNTM4ODE5Ni4xNzY4OTI1NDQ4LjIzODk3MTg2OC4xNzY4OTMxNjk0LjE3Njg5MzE4Njc.)
> which is extremely toxic!! Therefore the parts of this protocol that
> utilize TRI-reagent needs to be done inside of a active fume hood. In
> addition the waste produced during this protocol needs to be disposed
> of in the proper waste receptical.

------------------------------------------------------------------------

### Equipment and Reagents Needed:

- 1 x MagBind Tube Stand (Green one)
- 1 x Multi-tube vortex (Name Pending)
- 1 x Pipette-10 + Tips
- 1 x Pipette-200 + Tips
- 1 x Pipette-1000 + Tips
- 1 x Centrifuge (i.e. “Taz” placed in the 4ºC walk-in freezer)
- 3mm steal beads (1 per sample)

| Reagents                |     x 1 sample     | x 12 samples | x 24 samples |
|:------------------------|:------------------:|:------------:|:------------:|
| Tri-Reagent             |      1000 uL       |    12 mL     |    24 mL     |
| Mag Beads               |       20 uL        |    240 uL    |    480 uL    |
| DNA/RNA Wash 1 Buffer   |       500 uL       |     6 mL     |    12 mL     |
| DNA/RNA Wash 2 Buffer   |       500 uL       |     6 mL     |    12 mL     |
| EtOH (Two Plates)       |     500 uL x 2     |   6 mL x 2   |  12 mL x 2   |
| RNA Prep Buffer         |       500 uL       |     6 mL     |    12 mL     |
| DNase/RNase Free Water  |       100 uL       |    1.2 mL    |    2.4 mL    |
| 1-Bromo-3-chloropropane |       100 uL       |    1.2 mL    |    2.4 mL    |
| DNA/RNA Shield          | 200 uL (as needed) |    2.4 mL    |    4.8 mL    |

## Setup and Preparation:

### Extraction Plate Setup:

1.  Using your laptop or lab computer navigate to the
    VirusPlusLab/Screening/Blood_RNA_Seq/
2.  Fill out the
    [template](https://liveumb-my.sharepoint.com/:x:/r/personal/nichola_hill_umb_edu/Documents/VirusPlusLab/Screening/Blood_RNA_Seq/Raw_sample_TEMPLATE_UMB.xlsx?d=wc5a8e2974b524b30bbd46593014086eb&csf=1&web=1&e=rDQWN3)
    with the sample vial ID’s and save with the extraction date
    (YYYY-MM-DD).
3.  Print out the extraction template and the current extraction
    [protocol](https://github.com/Jonathan-Dain-42/RNA-Blood-Phenol-Extraction/blob/main/RNA-Blood-Phenol-Extraction-Protocol.mkd) -
    if not done already - for use during the extraction.

### Bead Sterilization:

1.  Confirm that you have the correct amount of 3mm steel beads
    sterilized for use in this protocol. You should have 1 per sample.
2.  If additional beads need to be sterilized, place additional beads in
    a small autoclave bag and run using the 1st floor autoclave with the
    HD45 cycle.
3.  Once beads are autoclaved, spray with RNA-Zap inside of the
    biosafety cabinet (room 3204).

### Buffer Preparation:

1.  If not done already: Add 20 ml (R2100, R2101) or 80 ml (R2102,
    R2103) of isopropanol to the MagBead DNA/RNA Wash 1 concentrate and
    mix well.
2.  If not done already: Add 30 ml (R2100, R2101) or 120 ml (R2102,
    R2103) of isopropanol to the MagBead DNA/RNA Wash 2 concentrate and
    mix well.

### Kingfisher Robot Preparation:

1.  Turn the bench-top Kingfisher Flex robot on.
2.  Run a maintenance check of the Kingfisher robot. Use ‘→’ arrow to
    navigate to maintenance tab (i.e. the spanner icon), scroll down to
    maintenance checks (spanner & list icon). Select “Check_96dw_tips”
    program and start. Load the tip comb and ‘Tip Pickup’ plate.
3.  Once the maintenence check is done. Start the tri-reagent KF
    protocol. Use the ‘→’ to navigate to the RNA tab, select “**enter
    protocol name**” and press start.

## Sample Preparation:

> 🦆 🧪 Note: This protocol is designed for use with **avian whole
> blood** samples stored in **DNA/RNA Shield**.

1.  Prior to thawing samples turn on biosafety cabinet (BSC) in 3204 and
    let blower “go” for 15 minutes. Wipe down inside of BSC with
    quartricide and RNase Zap. Additionally wipe down grey countertops
    with quartricide and outside of Kingfisher robot with both
    quatricide and RNase Zap.

2.  Thaw frozen blood vials inside of BSC (room 3204). If blood sample
    was not stored in DNR/RNA shield, add *200uL* of DNA/RNA shield to
    *50uL* of blood sample and mix pipette mix before step 2.

3.  While the samples are thawing label 7 x Kingfisher 96-deep well
    plates in the following order: Samples, DNA/RNA Wash 1, DNA/RNA Wash
    2, Ethanol Wash 1, Ethanol Wash 2, RNA Prep Buffer, Elution.

4.  Add the following reagents to each well in each plate in order.

5.  Add *500uL* MagBead DNA/RNA Wash 1 to each well in the DNA/RNA Wash
    1 plate.

6.  Add *500uL* MagBead DNA/RNA Wash 2 to each well in the DNA/RNA Wash
    2 plate.

7.  Add *500uL* ethanol (96-100%) into both ethanol wash plates.

8.  Add *500uL* RNA Prep Buffer to each well in the RNA Prep Buffer
    plate.

9.  Add *50uL* DNase/RNase free water to each well in the elution plate.

10. Load the places (minus the sample plate) onto the robot.

11. Once samples are thawed aliquot ~*100uL* of Blood Stored in DNA/RNA
    Shield into a sterile 2mL Eppendorf.

12. Centrifuge your 100uL aliquot in 4ºC centrifuge for 1 min at 5,000 -
    8,000 x g. This will lightly pellet the blood and allow you to
    remove a significant proportion of DNA/RNA shield. You may leave
    some behind but it is not recommended to leave more than ~20uL or
    shield.

13. **Move samples from BSC (room 3204) to fume hood (near Moyer’s lab
    benches).**

14. To each 2mL eppendorf tube add *1000uL* of Tri-Reagent.

15. Add sterile 3mm bead and vortex for 10 minutes using the multi-tube
    vortex.

## Phase Seperation:

1.  Add *100μl* cold 1-Bromo-3-chloropropane to each sample, shake
    vigorously for 20 seconds, then incubate at room temperature 10
    minutes.
2.  In the cold centrifuge spin at 4°C for 30-60 minutes at 12,000 x g
    (or max speed).
3.  Check phase separation: 50-60% of the volume should be clear aqueous
    phase. If separation is poor, add an additional 100 μl
    1-Bromo-3-chloropropane and repeat shake-incubate-spin step.
    Centrifugation separates the mixture into 3 phases: a colorless
    upper aqueous phase containing total RNA, an interphase containing
    DNA, and the red organic phase containing proteins.
4.  Carefully collect up to 500 μl of the aqueous phase, making sure not
    to disturb interphase or lower organic phase, and place in sample
    plate taking care to place sample into correct well of sample plate.
    Discared the interphase and lower organic phase. *Note this must be
    discarded in the proper waste receptical.*

> 💡 Here is a visual example of [Phase
> Seperation](https://cdn.shopify.com/s/files/1/0803/9419/1166/files/1_6905ba21-b3eb-4a34-9355-94e0bc796bac_1024x1024.jpg?v=1751352495)

## RNA Purification:

1.  Add equal volume of ethanol (95-100%) to recovered aqueous phase in
    each well, pipette mix twice.
2.  Add *20uL* MagBinding Beads to each well of the sample plate.
3.  Load sample plate onto Kingfisher robot in room 3204.

> 🛠️ **The rest of this protocol will be performed by the benchtop
> Kingfisher Flex robot in room 3204 using a custom script. Buffers are
> already dispensed into deep well plates the robot is manually moving
> the beads.**

4.  Mix well for 10 minutes then pellet the beads, and discard the
    cleared supernatant.
5.  Add *500uL* MagBead DNA/RNA Wash 1 and mix well. Pellet the beads,
    and again discard the supernatant.
6.  Add *500uL* MagBead DNA/RNA Wash 2 and mix well. Pellet the beads,
    and again discard the supernatant.
7.  Add *500uL* ethanol (96-100%) and mix well. Pellet the beads, and
    again discard the supernatant.
8.  **Repeat Step 6 of RNA Purification.**
9.  Dry the beads for 10 minutes or until fully dry.
10. Add *100uL* of DNase/RNase-Free Water and mix well for 5 minutes.
11. Elute RNA into 100uL DNase/RNase free water and remove beads.
12. Off of the robot, manually aliquot the eluted RNA into a labeled
    clean micro-centrifuge strip.
13. Aliquot 2.5 ul of RNA for quantitation into strip tubes. Use 1 μl
    for Qubit, 1 μl for Bioanalyzer, with the remaining 0.5 μl to
    account for pipetting error. Store RNA in -80°C.
14. Place eluted RNA into -80ºC for storage until further
    processing/sequencing.

## Decontamination and Clean-up:

1.  Dispose of all reagents that came in contact with TRI-Reagent (tips,
    tubes, aqueous waste, etc.) into the label waste container.
2.  Close and seal all open reagents and return to proper storage
    locations/temperatures.
3.  Wipe down area with ethanol and remove vortex from fume hood.
4.  Remove “Taz” from 4ºC walk-in freezer and place back on lab bench in
    3200.
5.  Wipe down BSC, grey counters, and Kingfisher robot with quatricide.
6.  Let the BSC blower blow for an additional 15-minutes then turn off
    BSC.
