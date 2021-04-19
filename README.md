# NHANES_Data_Analysis
The National Health and Nutrition Examination Survey (NHANES) is a cross sectional database that have been used to examine the prevalence of sedentary lifestyle related chronic diseases. Inadequate dietary, nutritional, and behavioral habits, household environment, whole body, and bone measurements etc. which might risk of causing such severe illnesses. This project is aimed to investigate and analyze various data mining techniques for prediction of frequent chronic diseases in U.S. adults who participated in 2017-2018 NHANES dataset. The main focus is on using Hybrid AI Model to estimate the association among all the features of NHANES dataset and classify hypertension diseased participants. This paper utilized a highly imbalanced dataset of 8366 with 81.20% participants with no hypertension, and 18.80\% participants with hypertension. Our results shows the best accuracy of 94% with Hybrid AI model which can be contributed to the health domain in identifying the person with risk of having hypertension by taking all the health prospects into the consideration.

The data for this can be found on https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?BeginYear=2017 and the analysis including preprocessing of the data is in different jupyter notebooks which is in same repository.

NHANESPreprocessing.ipynb - Initial preprocessing of NHANES dataset for around 2500 participants.

NHANESMerge_Hybrid.ipynb - Merging and preprocessing of NHANES dataset for every participant.

NHANESExploratoryAnalysis.ipynb - NHANES Data exploration.

NHANES_Traditional_Scenario_1.ipynb - Traditional ML scenario for participants with top five diseases which are around 2500.

NHANES_Traditional_Scenario_2.ipynb - Traditional ML scenario for all individuals.

NHANES_NeuralNetworks_CNN_Approach.ipynb - Application of CNN on NHANES dataset due to the understanding of data complexity. (Overkill model)

NHANES_NeuralNetworksApprach_3RF2ANN_ANN.ipynb - Hybrid approach of 3 Random Forest and 2 ANN models passed into an ANN model for NHANES dataset.

NHANES_NeuralNetworksApprach_Smote_3RF2ANN_ANN.ipynb - Hybrid approach of 3 Random Forest and 2 ANN models passed into an ANN model using SMOTE technique for NHANES dataset.

NHANES_NeuralNetworksApprach_5RF_ANN.ipynb - Hybrid approach of 5 Random Forest models passed into an ANN model for NHANES dataset.

NHANES_NeuralNetworksApprach_Smote_5RF_ANN.ipynb - Hybrid approach of 5 Random Forest models passed into an ANN model using SMOTE technique for NHANES dataset.

NHANES_NeuralNetworksApprach_LDA_ANN.ipynb - Best Hybrid approach of LDA models passed into an ANN model for NHANES dataset.

NHANES_NeuralNetworksApprach_Smote_LDA_ANN.ipynb - Best Hybrid approach of LDA models passed into an ANN model using SMOTE technique for NHANES dataset.
