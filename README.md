# TNBC-PGx
This is page is the data and code repository for the manuscript entitled:\
*Targeting neddylation and sumoylation in chemoresistant triple negative breast cancer.*\
Powell and Rinkenbaugh et al. 2024 [Submitted/In Review]

**Content:**<br>
<pre>
<ins>Item</ins>				  <ins>Description</ins>	
~/data/db                    	  PPI networks and MSigDB pathways used during analysis.
~/data/Primary                    All dataframes that are required to run "TNBC PGx notebook.Rmd" and replicate primary analysis.
~/data/Public			  Drug response and transcriptomic data that was downloaded from public domain databases or primary literature.
~/data/Validation		  All dataframes that are required to run the "TNBC PGx notebook2.Rmd" and replicate analysis for validation/PEV time studies studies                   
~/Reports/*                 	  Pre-computed outputs from the Rmd. Subfolders follow the naming convention of their parent Rmd notebook. Interactive HTML files likely need to be downloaded before opening
1_Primary.Rmd     		  Annotated Notebook to regenerate key figures and exploratory analysis
2_Public.Rmd			  Annotated Notebook to regenerate key figuree for data downloaded from public resouces (e.g. DepMap, CTD2, GDSC)
1_Validation.Rmd    		  Annotated Notebook to regenerate key figures for the validation/PEV time studies studies
TNBC PGx notebook.RData   	  Binary of the notebook data
Readme.md                 	  This file
</pre>

**Code:**\
All code was developed using R 4.3.1 using RStudios. All code was developed on a Dell Precision 7920 with an Intel Xeon 8C/16T 3.56 Ghz Processor and 128 Gb RAM.\
Approximate runtime for the complete notebook is with in a hour. Modeling steps can take a few hours to a day depending on parrallization settings.
