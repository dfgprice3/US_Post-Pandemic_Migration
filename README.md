# US_Post-Pandemic_Migration
Prediction of county-level migration following COVID pandemic.

The COVID pandemic of 2020 changed people’s lives. Lockdowns occurred in most of the Unites States forcing many employees and students to work from home. This arrangement persisted for months. Companies are allowing people to perform jobs remotely or in a hybrid environment, and employees are using this benefit to consider changes to their living situation. With fewer employees tied to a specific geographic location, many are opting to relocate for family, enjoyment, financial, or just a change in scenery. 

**Approach**
The created model predicts migration of the US population by county and explain the factors that influence migration patterns. Random Forest regressors were used to develop the model, and SHAP values were used to explain contributing factors to the model. The US_Migration_Prediction_Notebook provides the code.

**Data Summary**
The United States Federal Government (USFG) publishes statistics on domestic migration. Domestic migration data from April 2020 through July 2021 will be used as our target variable as it most closely represents the period immediately following the pandemic and shutdown. The study will be conducted at the county level.

Many factors may contribute to a person’s decision to move. The Indiana Business Research Center (IBRC) at Indiana University publishes health, economic, and quality of life statistics for each county. The IBRC data set will be joined to the census data at the county level and will form over 100 features for each county. See Appendix for full list of features and the Data Preparation section for information on transformations and variable reductions.  

The supporting files are included in this repository, and processing is shown in the notebook.
