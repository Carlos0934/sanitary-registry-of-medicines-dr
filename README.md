
# Sanitary Registry of Medicines Analysis 

This project contains the code and data used in the analysis of the Sanitary Registry of Medicines in Dominican Republic
for analysis of the data and the generation of the report.

## Table of Contents

1. [Design goals](#design-goals)

2. [How to run the project](#how-to-run-the-project)

3. [Methodology](#methodology)

4. [Data](#data)

5. [Results](#results)

6. [Conclusions](#conclusions)

7. [Next steps](#next-steps)

## Design goals


* Determine the number of medicines by manufacturer.

* Determine the distribution of medicines by pharmaceutical form.

* Determine the historical evolution of the number of medicines requested by manufacturer.
 
* Determine which factors influence the durability of a medicine and create a model that allows to predict the expiration of a medicine based on the data of the sanitary registry.



## Data

The data used in this project is the Sanitary Registry of Medicines in Dominican Republic. This data was obtained from the
Ministry of Public Health of the Dominican Republic. The data is available in the following link: 
[Sanitary Registry of Medicines](https://datos.gob.do/dataset/registro-sanitario-de-productos-farmaceuticos)

### Raw Data

The raw data is available in the `data/raw` folder. All the data is in CSV format.

For the analysis, the following files were used:

* `sanitary_registry_medicines.csv`: This file contains the data of the Sanitary Registry of Medicines


### Processed Data

The processed data is available in the `data/processed` folder. All the data is in CSV format. The following files were
generated:

* `sanitary_registry_medicines.csv`: This file contains the data of the Sanitary Registry of Medicines with cleaned and formatted values.


### Final Data

The final data is available in the `data/final` folder. All the data is in CSV format. The following files were

* `sanitary_registry_medicines.csv`: This file contains the data of the Sanitary Registry of Medicines  without outliers.



## Methodology

The methodology used in this project is the following:

1. Data cleaning and formatting of the data. This step is done in the `src/process.ipynb` notebook.

2. Data analysis. This step is done in the `src/analysis.ipynb` notebook.

3. Data visualization. This step is done in the `src/report.ipynb` notebook.

4. Data modeling. This step is done in the `src/prediction.ipynb` notebook.


## Conclusions


## Next steps


