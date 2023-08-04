# TNBC-PGx
This is page is the data and code repository for the manuscript entitled:\
*Neddylation as a therapeutic target in chemoresistant triple negative breast cancer.*\
Powell and Rinkenbaugh et al. 2023 [Submitted/In Review]\

**Content:**<br>
<pre>
~/data                    All dataframes that are required to run "TNBC PGx notebook.Rmd" and replicate primary analysis.
~/data2                   All dataframes that are required to run the "TNBC PGx notebook2.Rmd" and replicate analysis for validation/PEV time studies studies
~/Reports                 Pre-computed outputs from the Rmd. Interactive HTML files likely need to be downloaded before opening
TNBC PGx notebook.Rmd     Annotated Notebook to regenerate key figures
TNBC PGx notebook2.Rmd    Annotated Notebook to regenerate key figures for the validation/PEV time studies studies
TNBC PGx notebook.RData   Binary of the notebook data
Readme.md                 This file
</pre>

**Data Description:**<br>
<pre>
*Drug_AUC.csv            Table of area under the curve values for the in vitro high throughput screen
*Drug_metadata.csv       Table of drug annotations
*PDX_metadata.csv        Table of PDX annotations
*RNA_combat.220304.csv   Table of combat normalized gene expression values.
</pre>

**Code:**\
All code was developed using R 4.3.1 using RStudios. All code was developed on a Dell Precision 7920 with an Intel Xeon 8C/16T 3.56 Ghz Processor and 128 Gb RAM.\
Approximate runtime for the complete notebook is with in a hour.
