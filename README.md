# DP1_Xray_public
This repo contains the code needed to generate the datasets and plots for the X-ray sources to DP1 crossmatch paper. It should be run on the Rubin Science Platform.  

## Data Products

The X-ray catalog for all sources observed in DP1 is found at `data/final_data_products/xray_in_DP1.csv`.  
  
Subsets containing all columns of the x-ray catalogs (e.g. CSC2.1) making up the above catalog are found in the  `data/final_data_products/full_xray` folder  

You will need to download the relevant X-ray catalogs to run the code on your own as these are quite large and cannot be uploaded to GitHub.  

##### CSC2.1 
This was downloaed with the CSCview application: https://cxc.cfa.harvard.edu/csc/download/   
##### 4XMMDR14
Reduced binary catalog from: http://xmmssc.irap.omp.eu/Catalogue/4XMM-DR14/4XMM_DR14.html
##### 2SXPS
Clean subset: https://www.swift.ac.uk/2SXPS/
##### XMMSL3
http://xmmssc.irap.omp.eu/Catalogue/XMMSL3/XMMSL3.html
##### eRASS DE DR1
eRASS1 main catalog: https://erosita.mpe.mpg.de/dr1/AllSkySurveyData_dr1/Catalogues_dr1/


### Notes
...
## Notebooks

Notebooks in `notebooks\data_processing` provide all the code to generate the final data products. Notebooks in `notebooks\analysis`  contain the code to generate figures.  

The notebook `notebooks/analysis/make_plots.ipynb` touches most of the files available in `data/final_data_products` and produces the plots in the paper  
