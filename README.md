# gusto_adversity_microbiome_SEF

**NOTE**: Scripts that were updated or created during the review process have the extension "_PNASreviews". 

Analysis scripts used for the manuscript "Multigenerational adversity impacts on gut microbiome composition and socioemotional functioning in early childhood"

Preprint at: https://psyarxiv.com/64m9g/, OSF project at: https://osf.io/c564x/, Paper at: https://www.pnas.org/doi/10.1073/pnas.2213768120.

These scripts are uploaded as .html files knitted from R markdown or Jupyter notebook (depending on coding language) so that code and output can be easily viewed together. However, the .html files cannot be visualized directly within GitHub. Please follow the instructions below to open and view them. 

## To open the .html files: ##
1. Click on file, then click "Download". This will open the raw version of the file. 
2. Right click on this page of text and hit "Save as..."
3. Download and save as .txt file
4. Change extension from .txt to .html
5. Click to open in a web browser

## The following scripts are included in this repository: ##
__Main analysis script:__ gusto_microbioM24_adversity_cbcl_sharingversion.html.  

__Metadata wrangling script:__ gusto_metadata_wrangle_sharingversion.html.   

__Questionnaire data cleaning scripts:__
  1. gusto_age_cleaning.html
  2. gusto_biotics_cleaning.html
  3. gusto_breastfeeding_cleaning.html
  4. gusto_cbcl_fran_sharingversion.html
  5. gusto_cbcl_gi_scoring_sharing.html
  6. gusto_ctq_scoring_sharingversion.html
  7. gusto_deliverymode_scoring.html
  8. gusto_income_household_cleaning.html
  9. gusto_leq_scoring.html
  10. gusto_stai_scoring_sharing.html

__Microbiome data processing script:__ gusto_M24_M48_microbiota_processing.html.  

## Running Order ##
To perform the analyses for this manuscript, the following notes on script running order were used:
1. Questionnaire data cleaning scripts and microbiome data processing scripts were run before the others
2. Within the questionnaire data cleaning scripts, gusto_cbcl_fran_sharingversion.html was run before gusto_cbcl_gi_scoring_sharing.html
3. Metadata wrangling script was run after questionnaire data cleaning and microbiome data processing scripts
4. Finally, main analysis script was run last. 
