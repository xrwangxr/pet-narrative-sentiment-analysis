# “I Love You Just as Much”: Emotional Valence and Composition in Owners’ Narratives About Dogs and Cats

## Author

Xinru Wang

## Project Overview

This project examines whether emotional language differs when pet owners describe their dogs versus their cats in interview narratives. Pet-related narrative segments were extracted from interview transcripts and analyzed in R using lexicon-based sentiment analysis.

The project explores:
- whether overall emotional valence differs between dog and cat narratives
- whether specific emotion categories (e.g., joy, trust, sadness, anticipation) differ between dog and cat narratives

Analyses were conducted using the sentimentr package for sentiment scoring and the NRC Emotion Lexicon for emotion classification. Mixed-effects models were used to account for multiple narrative segments contributed by the same participant.

This research contributes to growing work on human–animal relationships and multispecies family studies by examining how people emotionally talk about their companion animals through language.

## Repository Contents

- `data/` *(restricted)* → documentation and materials related to the project dataset  
- `code/` → R scripts used for sentiment analysis and statistical modeling  
- `output/` → figures, tables, and other visual outputs generated from the analyses  
- `docs/` → thesis PDF and additional supporting materials   

## Data

The data used in this project were derived from interview transcripts collected as part of a broader qualitative study on multispecies families and human–animal relationships.

For the present project, pet-related narrative segments discussing companion animals were extracted and analyzed using lexicon-based sentiment analysis techniques in R.

Due to participant privacy, confidentiality agreements, and IRB restrictions, the original interview transcripts and processed narrative data are not publicly available.

## Code / Analysis

Analyses were conducted primarily in R using packages including tidyverse, sentimentr, tidytext, and lme4.

Scripts included in this repository were used for:
- sentiment analysis
- emotion category analysis
- mixed-effects modeling
- data visualization

The repository is organized to document the primary workflow used throughout the project and to make the analysis process easier to understand and reproduce.

## Thesis Link

Full manuscript is currently withheld pending future publication.

## Citation

[![DOI](https://zenodo.org/badge/1242920315.svg)](https://doi.org/10.5281/zenodo.20347460)
