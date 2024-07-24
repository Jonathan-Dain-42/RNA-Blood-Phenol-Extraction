# Phenol tRNA Extraction Protocol with Phase Sep and Kingfisher
@author Jonathan Dain   

@github https://github.com/Jonathan-Dain-42
# Purpose:
This protocol has been refined for use of RNA extraction from field collected whole avian blood samples preserved in DNA/RNA Shield which were then stored in a -80 °C freezer. The reagent volumes are setup to extract RNA from 20 blood samples at a time. 

This protocol is adapted from the manufacturers instructions on the Zymo Direct-zol-96 MagBead RNA kit. Their protocol is found [here](https://files.zymoresearch.com/protocols/_r2100_r2101_r2102_r2103_r2104_r2105_direct-zol-96_magbead_rna.pdf). It was then modified using information in Johanna Harvey's RNA extraction that can be found [here](https://github.com/JAHarvey/RNA-Blood-preservation-extraction). 
# Before Starting:
## Safety Information:
- TRI-Reagent contains the compound phenol which is extremely toxic. Therefore this protocol needs to be done inside of a active fume hood for the parts that utilize the TRI-Reagent. 
- In addition the waste of this protocol needs to be disposed of in the proper waste receptical.
## Materials Needed:
- 1 x MagBind Tube Stand (Green one)
- 1 x Multi-tube vortex
- 1 x P-10 +Tips
- 1 x P-200 + Tips
- 1 x P-1000 + Tips
- 2000 uL TRI-Reagent
- 20uL Protienase K (reconstituted)
- 4020uL EtOH (100%)
- 400uL Mag Bind Beads
- 10mL DNA/RNA Wash 1 Buffer
- 10mL DNA/RNA Wash 2 Buffer
- 40mL EtOH (100%) - For ethanol washing
- 1000uL DNase 1 Reaction Mix
- 10mL RNA Prep Buffer
- 1000uL DNase/RNase Free Water
- 1-Bromo-3-chloropropane (100uL per sample) - Hold on Ice.
# Extraction Setup and Preperations:
## Digital Plate Setup:
1. Using your laptop or lab computer navigate to the VirusPlusLab/Screening/Blood_RNA_Seq/
2. Fill out the [template](https://liveumb-my.sharepoint.com/:x:/r/personal/nichola_hill_umb_edu/Documents/VirusPlusLab/Screening/Blood_RNA_Seq/Raw_sample_TEMPLATE_UMB.xlsx?d=wc5a8e2974b524b30bbd46593014086eb&csf=1&web=1&e=rDQWN3) with the sample vials and save with the extraction date (YYYY-MM-DD).
3. Print out the extraction template and the current extraction [protocol](https://github.com/Jonathan-Dain-42/RNA-Blood-Phenol-Extraction/blob/main/RNA-Blood-Phenol-Extraction-Protocol.mkd) - if not done already - for use during the extraction. 
## Bead Sterilization:
1. Confirm that you have the correct amount of 3mm steel beads sterilized for use in this protocol. 
2. If additional beads need to be sterilized, place additional beads in a small autoclave bag and run using the 1st floor autoclave with the HD45 cycle. 
3. Once beads are autoclaved, spray with RNA-Zap inside of the biosafety cabinet (room 3204). 
## Buffer Preparation:
1. If not done already: Add 20 ml (R2100, R2101) or 80 ml (R2102, R2103) of isopropanol to the MagBead DNA/RNA Wash 1 concentrate and mix well. 
2. If not done already: Add 30 ml (R2100, R2101) or 120 ml (R2102, R2103) of isopropanol to the MagBead DNA/RNA Wash 2 concentrate and mix well. 
3. If not done already: Reconstitute each vial of lyophilized DNase I with DNase/RNase-Free Water in a conical tube (not provided).  Mix by gentle inversion and store frozen aliquots. 
  a. E1009-A (250 U), add 2.25 ml water.
4. If not done already: Reconstitute lyophilized Proteinase K at 20 mg/mL with Protienase K storage buffer and mix by vortex. (Use PK from kit R2132).

# Sample Preparation:
**Note: This protocol is designed for use with avian whole blood samples stored in DNA/RNA Shield.**
1. Thaw frozen blood vials inside of biosafety cabinet (room 3204). If blood sample was not stored in DNR/RNA shield, add *200uL* of DNA/RNA shield to *50uL* of blood sample and mix pipette mix before step 2.
2. Aliquot *100uL* of Blood Stored in DNA/RNA Shield into a sterile 2mL Eppendorf.
3. Add *5uL* of Protienase K solution to each sample. Incubate samples at room temp for 30 minutes. **(This is done per the Zymo Rep recommendation)**.
4. While the samples are incubating label 7 Kingfisher 96-deep well plates in the following order: Samples, DNA/RNA Wash 1, DNA/RNA Wash 2, Ethanol Wash 1, Ethanol Wash 2, RNA Prep Buffer, Elution. 
5. Add *500uL* MagBead DNA/RNA Wash 1 in the named plate. 
6. Add *500uL* MagBead DNA/RNA Wash 2 in the named plate.
7. Add *500uL* ethanol (96-100%) into both ethanol wash plates. 
8. Add *500uL* RNA Prep Buffer into the named plate.
9. Add *50uL* DNase/RNase Free water into the elution plate. 
10. **Move samples from biosafety cabinet (room 3204) to fume hood (near Moyers lab benches).**
11. For a 100uL sample add *100uL* of Tri-Reagent. 
12. Add sterile 3mm bead and vortex for 10 minutes.

# Phase Seperation:
1. Add *100μl* cold 1-Bromo-3-chloropropane, shake vigorously for 20 seconds, then incubate at room temperature 10-15 minutes.
2. On the cold centrifuge spin at 4°C for 30-60 minutes at 12,000 x g (or max speed).
3. Check phase separation: 50-60% of the volume should be clear aqueous phase. If separation is poor, add an additional 100 μl 1-Bromo-3-chloropropane and repeat shake-incubate-spin step. Centrifugation separates the mixture into 3 phases: a colorless upper aqueous phase containing total RNA, an interphase containing DNA, and the red organic phase containing proteins.
4. Carefully collect up to 500 μl of the aqueous phase, making sure not to disturb interphase or lower organic phase, and place in clean 96-well plate taking care to place sample into correct well.

#### **The rest of this protocol will be performed by the benchtop Kingfisher Flex robot in room 3204**

# RNA Purification:
1. Add equal volume of ethanol (95-100%) to sample lysed in TRI-Reagent, mix via vortex for 30 seconds.
2. Add *20uL* MagBinding Beads and mix well for 10 minutes.
3. Transfer tubes/plate to the magnetic stand until beads have pelleted, then aspirate and discard the cleared supernatant. *Note this must be discarded in the proper waste receptical.*   
4. Add *500uL* MagBead DNA/RNA Wash 1 and mix well. Pellet the beads, and again discard the supernatant.
5. Add *500uL* MagBead DNA/RNA Wash 2 and mix well. Pellet the beads, and again discard the supernatant.
6. Add *500uL* ethanol (96-100%) and mix well. Pellet the beads, and again discard the supernatant.
7. Repeat Step 6 of RNA Purification. 
8. Add *500uL* RNA Prep Buffer and mix well for 10 minutes. Pellet the beads and discard the supernatant.
9. **Repeat steps 6-7 of RNA Purification.**
10. Dry the beads for 10 minutes or until fully dry. 
11. Add *50uL* of DNase/RNase-Free Water and mix well for 5 minutes.
12. Transfer the tubes to the magnetic stand until beads have pelleted, then aspirate and dispense the eluted RNA into labeled microcentrifuge tube. 
13. Place eluted RNA into -80 unless for storage until further processing/sequencing. 

# Decon:
1. Dispose of all reagents that came in contact with TRI-Reagent (tips, tubes, aqueous waste, etc.) into the label waste container.
2. Close and seal all open reagents and return to proper storage locations/temperatures.
3. Wipe down area with ethanol and remove vortex from fume hood. 

 
