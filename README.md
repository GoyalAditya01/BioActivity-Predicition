# BioActivity-Predicition
Create a bioactivity prediction app using molecular descriptors (PADEL) and supervised machine learning (ML) and DL. The project allow you to extract and clean data from Chembl database in order to obtain IC50 of every studied molecule relative to a target protein of interest. IC50 values are associate to molecular and lipinski descriptors in order to generate a model that can predict bioactivity values of new single molecules or library of compounds.

modules must be used consequently, in order:

bioActivity_part1: search data for a specific target on Chembl database and make a dataframe, collect IC50 and SMILES values and calculate molecular descriptors by PADEL. Set descriptors as x and pIC50 as y. ** before closing the colab page (part1) you must save on your computer (or in google drive) dataset_with_padel_pIC50.csv file **.

bioActivity_part2: ** upload dataset_with_padel_pIC50.csv file **. Compare various ML models and find the best one to utilize for our project.

bioActivity_part3: Calculates descriptors from the genertaed smiles notation

bioActivity_part4: Perform linear regression with RandomForest regressor, generate the model (pkl) and predict IC50 of new molecules directly via colab worksheet.

bioActivity_part5: compares the performance of different models using lazy predict library.

bioActivity_part6:It's basically a web app built that allows you to upload pickle object (the model previously generated) and SMILES file (every dimension), read them and perform predictions. It makes possible to obtain results from every target protein model choosen by you!
 
