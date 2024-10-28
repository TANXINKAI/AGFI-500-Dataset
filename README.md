# AGFI-500-Dataset

## 1. Introduction

With rapid advancements in text-to-image generative models, AI-generated images (AGIs) are now widely used across entertainment, education, social media, and other fields. However, due to significant quality variation among AGIs, there is a pressing need for quality assessment models that align closely with human subjective ratings.

To address this need, we evaluated various popular AGI models, generated images using diverse prompts and model parameters, and gathered subjective scores based on perceptual quality and text-to-image alignment. This has allowed us to build the novel AGI subjective quality database, AGFI-500.

We believe that the detailed subjective scores in AGFI-500 will encourage the development of AGI quality models that more closely align with human perception at both the perceptual and alignment levels, ultimately enhancing the output of future AGI models.

## 2. Database Description

The **AGFI-500** database contains the following file:

**A. _data.csv_** (Image Id, quality perception, alignemnt)

Column1: Image identifier

Column2: Normalized MOS for subjective perception Quality Score (QS) 

Column3-4: Lower and higher confidence interval for Normalized MOS for Quality Score (QS)  

Column5: Normalized STD for quality perception subjective score.

Column6: Normalized MOS for subjective perception Alignment Score (AS) 

Column8-9: Lower and higher confidence interval for Normalized MOS for Alignment Score (QS) 

Column9: Normalized STD for alignment perception subjective score.


