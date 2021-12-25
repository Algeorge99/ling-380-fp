# ling-380-fp
Final Project for Linguistics 380 -- Yelp reviews!

Project created by Kelsey Evans, Alan George, and Justin Miller.

* The original .csv is too large for github, but can be found here: https://www.kaggle.com/yelp-dataset/yelp-dataset/version/6?select=yelp_review.csv
* Balancer.ipynb balances the data so that all reviews have an equal number, then outputs "yelp_balanced.csv" to the working directory.
* bert_for_sequence_classification.ipynb adapts code from here: https://www.kaggle.com/barelydedicated/yelp-review-predictions-using-huggingface-bert/notebook and runs the BERT model 
* The data_analysis_on_examples.ipynb file compares performance on specific examples and needs qualifiers.csv, contradictory.csv, and figurative.csv from the csv_files folder


Relevant files:
*Balancer -- Pre-processer, used for balancing yelp dataset. Output in CSV folder
*Baseline Models_v3 -- Contains baseline models output
*Baseline Removal_Words -- Contains random sentence removal
*bert_for_sequence -- BERT model
*doc2vec code real -- doc2vec code
