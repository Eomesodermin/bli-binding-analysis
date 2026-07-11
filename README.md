# bli-binding-analysis

R analysis of **bio-layer interferometry (BLI / Octet)** data for characterising
**antibody–antigen binding kinetics**.

## What it does
`scripts/Ellie_antibody_binding.Rmd` takes exported BLI sensorgrams and:
- parses association / dissociation phases per sensor,
- plots binding curves grouped by analyte concentration,
- summarises binding responses to compare antibodies / conditions.

BLI measures binding in real time by detecting shifts in the interference pattern of white light
reflected from a biosensor tip as molecules associate and dissociate — a label-free way to assess
affinity and on/off kinetics.

## Usage
Open the `.Rmd` in RStudio and knit, pointing it at your exported Octet data.

---
Author: **Dillon Corvino** · [dilloncorvino.com](https://dilloncorvino.com)
