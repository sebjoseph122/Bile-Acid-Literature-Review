# Bile-Acid-Literature-Review

Within the Supplementary Code folder, you will find 3 files:

(1)  data_cleaning.ipynb

(2)  peripheral_data.csv

(3)  plot_generation.ipynb

And 1 folder:

(4)  Generated-Files


data_cleaning.ipynb cleans the raw data contained within peripheral_data.csv, generating 3 files:

(1)  peripheral_data_nm.csv  (contains all concentration units converted to nM)

(2)  peripheral_ibas_longform.csv  (contains all individual bile acid concentrations in longform to simply plotting)

(3)  peripheral_total_longform.csv  (contains all total bile acid concentrations in longform to simply plotting)

plot_generation.ipynb uses these 3 generated files to produce the main figures and supplementary figures.


You have 2 options:

(1)  Run data_cleaning.ipynb and then plot_generation.ipynb

(2)  Run plot_generation.ipynb in the Generated-Files folder
