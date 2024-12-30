# Churn-Customers
**Final Project: Dataset**

The telecom operator Interconnect would like to be able to forecast their churn of clients. If it's discovered that a user is planning to leave, they will be offered promotional codes and special plan options. Interconnect's marketing team has collected some of their clientele's personal data, including information about their plans and contracts.

**Interconnect's services:**<br>
&ensp; Interconnect mainly provides two types of services:<br>
&ensp; &ensp; -Internet. The network can be set up via a telephone line (DSL, digital subscriber line) or through a fiber optic cable.<br>
&ensp; &ensp; -Landline communication. The telephone can be connected to several lines simultaneously.<br>

&ensp; Some other services the company provides include:<br>
&ensp;&ensp;  -Internet security: antivirus software (DeviceProtection) and a malicious website blocker (OnlineSecurity)<br>
&ensp;&ensp;  -A dedicated technical support line (TechSupport)<br>
&ensp;&ensp; -Cloud file storage and data backup (OnlineBackup)<br>
&ensp;&ensp;  -TV streaming (StreamingTV) and a movie directory (StreamingMovies)<br>
	
The clients can choose either a monthly payment or sign a 1- or 2-year contract. They can use various payment methods and receive an electronic invoice after a transaction.

**Data Description:** <br>
&ensp; The data consists of files obtained from different sources:<br>
&ensp; &ensp; -contract.csv — contract information<br>
&ensp; &ensp; -personal.csv — the client's personal data<br>
&ensp; &ensp; -internet.csv — information about Internet services<br>
&ensp; &ensp; -phone.csv — information about telephone services<br>
 
 In each file, the column customerID contains a unique code assigned to each client.
 
--------------------------------------------------------------------
 <ins>The Proposed work Plan</ins>
--------------------------------
**Goal:** Develop a model to predict user churn

Steps:

1. INTRO<br>

2. Download the data<br>

3. Explore the data to determine how to treat the data in the preprocessing step<br>

4. Perform preprocessing for the data<br>

    - Merge the data from all dataframes to one main dataframe<>
    - Change column names to underscore lowercase format<br>
    - Convert columns to desired data type<br>

5. Perform EDA to explore the data in depth<br>

6. Feature Engineering<br>

7. Test various classification models against a dummy benchmark. Logistic Regression will be used in this case. 
    Use ROC-AUC and accuracy score for evaluation metrics. Fine tune models using cross-validation. 
    Incorporate gradient boosting techniques.<br>

8. Evaluate final model on test set.<br>

9. conclusion<br>
