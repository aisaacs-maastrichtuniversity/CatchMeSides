# CatchMeSides

This repository contains the R scripts used for the analyses described in the paper _Lateral atrial expression patterns provide insights into local transcription disequilibrium contributing to disease susceptibility_. The manuscript is currently under review in Circulation: Genomic and Precision Medicine.

The paper describes a large RNA sequencing dataset generated from atrial tissue biopsies. The biopsies, obtained from five centers in Europe, were collected during open chest cardiac procedures and include both left and right atrial samples. For a subset of patients, both left and right atrial biopsies were available. These were used as a discovery cohort, free from confounding due to comorbidities, medication use, age, gender, etc. The remaining samples, for which tissue from only one atrial side was collected, were utilized as an independent validation cohort.

The included scripts are:
1. Rscript_catchme_sides_deseq2.txt, which was used to generate the left/right differential expression comparisons in the paired and unpaired samples.
2. Rscript_catchme_sides_dexseq.txt, which was used to generate the left/right differential exon usage comparisons in the paired and unpaired samples.
3. Rscript_catchme_sides_interactions.txt, which was used to assess interactions between atrial sidedness and atrial fibrillation and heart failure.
4. Rscript_catchme_sides
