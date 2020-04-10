# Predictive modelling of Medicare data from CMS 2014
The provider payment [data] released by CMS (http://download.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Downloads/Medicare_Physician_and_Other_Supplier_NPI_Aggregate_CY2014.zip.) 
This [page] (https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Physician-and-Other-Supplier2014.html) gives some background of the data. 
This [technical document] (https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Downloads/Medicare-Physician-and-Other-Supplier-PUF-Methodology.pdf) provides some critical information such as the definition of each variable.

The data set contains two types of providers: individual and organization. We only look at individuals for all the questions in this exercise (nppes_entity_code equals 'I').
The data was used to predict the "pcp" type of the provider given the existing features in the model. “pcp” has a value of 1 if the provider’s specialty (provider_type) is either “Internal Medicine” or “Family Practice”; “pcp” has a value of 0 if the provider’s specialty (provider_type) is neither “Internal Medicine” nor “Family Practice”

# Workflow
The code contains extraction, cleaning, and exploration of the data. Followed by modelling the data to predict the class of provider type using features within the data. 

# Applications
Data visualization, feature selection and engineering, machine Learning, evaluating model metrics

# Built With
- [Jupyter Notebook](https://jupyter.org)

