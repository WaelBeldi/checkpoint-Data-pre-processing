# What You're Aiming For

In this checkpoint, we aim to explore and preprocess the billing history of the Tunisian electricity and gas company's customers from 2005 to 2019, focusing on understanding the data structure, handling missing values, performing descriptive analysis, and transforming categorical variables into numerical formats.

## Instructions

In this checkpoint, we are going to work on the billing history of the Tunisian electricity and gas company and apply what you learned in pre-processing chapter.

**Dataset description :**

The provided dataset contains the billing history of the Tunisian electricity and gas company's customers from 2005 to 2019.

➡️ **Dataset link:** [https://drive.google.com/file/d/1DVFNq8Gsf9wFZznGafhykVmVHLvAclGo/view](https://drive.google.com/file/d/1DVFNq8Gsf9wFZznGafhykVmVHLvAclGo/view)

1. Load the dataset, display the ten first lines, store the results in a variable called 'client_0_bills'.
2. What is the data type of the 'client_0_bills' variable ?
3. Display the general information of the dataset and try to answer the following questions :

   * How many rows and columns do we have in this dataset ?
   * How many categorical features are present in the dataset ?
   * How much memory space does the dataset consume ?
4. Inspect the dataset for potential missing values.
5. Select your strategy to handle missing values, and tell us why you had made that choice.
6. Run a descriptive analysis on numeric features (columns).
7. Select the bills records for the client with an id ='train_Client_0', using 2 methods.
8. Transform the 'counter_type' feature to a numeric variable using the encoder of your choice.
9. Delete the 'counter_statue' feature from the Dataframe.
