# MasterThesis

Repository with all data and scripts of master thesis ***Modelling of factors influencing the share of public transport tickets in Swiss municipalities including cluster analysis*** from Gabriel Peier 

## Data storage
- The personal Google Drive account from Gabriel Peier was used to store all data, scripts, outputs and visualizations. 
- Due to storage limitations, the data could not be stored in the GitHub Repository
- Access can be granted to the whole Master's Thesis Drive storage via: gabrielpeier@gmail.com (this can make the process easier)
- If used in your own Drive Storage: Adapt all pathes accordingly in the script: All Data must be placed in the Data folder with the sub-pathes as described in the different chapters of this script, otherwise adapt it.

## ETL_Influence_factors.ipynb
The script "ETL_Influence_factors.ipynb" is used to go through all the necessary steps in order to process the data according to the Master's thesis to establish a working database for the modelling of possible influence factors on Public Transport in Switzerland.



All data are can be accessible free of charge and are found here (with name according to chapter 4)
- ga_hta_list: https://opentransportdata.swiss/de/dataset/ga-hta-liste1
- verbundabo_list: https://opentransportdata.swiss/en/dataset/verbundsabos
- STATPOP2020_GMDE: https://www.bfs.admin.ch/bfs/en/home.assetdetail.19106709.html
- population: https://www.bfs.admin.ch/bfs/en/home/statistics/catalogues-databases.assetdetail.su-d-01.02.03.07.html
- stations_list_bav: https://opentransportdata.swiss/de/dataset/bav_liste
- stop_count: https://opentransportdata.swiss/de/dataset/halte
- town_directory: https://www.cadastre.ch/en/services/service/registry/plz.html
- cars_per_municipality: https://www.pxweb.bfs.admin.ch/pxweb/de/px-x-1103020100_111/-/px-x-1103020100_111.px/
- inbound_comm: https://www.atlas.bfs.admin.ch/maps/13/de/3139_3138_3134_3114/3561.html
- outbound_comm: https://www.atlas.bfs.admin.ch/maps/13/de/3141_3140_3134_3114/3581.html
- dist: https://zenodo.org/record/3379492 (2 different zip files to download; "OeV_Reisezeit_Distanz" and "Strasse_Reisezeit_Distanz" with each 2 corresponding mtx files) 

## Influence_factors.Rmd
This script uses the above created dataset and calculates possible influence factors on the share of Public Transport Subscriptions via a Generalized Linear Model with family binomial and quasibinomial. See the script for detailled descriptions.
