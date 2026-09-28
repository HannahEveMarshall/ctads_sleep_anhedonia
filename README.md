# Sleep and the Daytime Course of Anhedonia in Adolescent Depression: An Ecological Momentary Assessment Study

This repository (still in development) contains materials corresponding to the paper "Sleep and the Daytime Course of Anhedonia in Adolescent Depression: An Ecological Momentary Assessment Study" by Hannah E. Marshall, Linda Nduka, Tahjanee Givens, Caroline Miller, Mollie Davis, Chana Engel, Kenneth Towbin, Daniel Pine, and Katharina Kircanski

## Synopsis

This study uses high-density ecological momentary assessment (EMA) data from the Characterization and Treatment of Adolescent Depression Studies (CTADS) cohort (collected from 2023 to 2026) to test sleep disturbances and sleep duration as predictors of anticipatory and consummatory anhedonia, and determine whether effects exhibit diurnal variation.

## Preregistration

Our sample, hypotheses, and analytic plan were preregistered on Open Science Framework at https://osf.io/r685d/.

## Repository Structure

```bash
/ctads_sleep_anhedonia
├── README.md
├── code
│   └── pipeline.Rmd                 # Full statistical pipeline
├── data
│   └── public_data.csv              # Deidentified data only from participants who consented to data sharing
├── figures
│   ├── figure_1.jpg                 # Figure 1
│   └── figure_2.jpg                 # Figure 2
├── manuscript
│   └── manuscript.pdf               # Manuscript
└── supplementary_material
    ├── reproducible_results.pdf     # Reproducible results using data only from participants who consented to data sharing
    └── supplementary_material.pdf   # Supplementary materials accompanying manuscript
```

## Note on Publicly Accessible Data

The publicly available dataset (_public_data.csv_) only includes participants who explicitly consented to us sharing their deidentified data (_N_ = 61). Results reported in our manuscript are from analyses of the complete dataset (_N_ = 65), which includes participants who did not consent to data sharing. For the purposes of reproducibility, we have include the file _reproducible_results.pdf_, in which we report the results of our pipeline using the publicly available dataset.
