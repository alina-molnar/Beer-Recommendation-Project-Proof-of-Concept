# Beer-Recommendation-Project-Proof-of-Concept
Beer Recommendation Project (Proof of Concept)
ML models with H2O for predicting customer's preference using past ratings


Reproducibility statement
To ensure reproducibility of all my analyses I have deposited the Jupyter notebook containing the code in a Github repository https://github.com/alina-molnar/Beer-Recommendation-Project-Proof-of-Concept. The same repository contains raw data input, all results files, software requirements, final report, video presentation and PowerPoint presentation. Environment setup is listed in the above-mentioned Final Report file, chapter 1.2.1 Inventory of Resources.


Project Objective: Predict customer’s ratings of new beer using past preferences.
How: Build machine learning model that takes categorical data as input and  predicts numeric data output.


Methods used:
- Machine Learning
- Data Visualization

Technologies:
- Python
- H2O
- Matplotlib
- Numpy
- Pandas
- Seaborn
- Scipy

Project Description
In Beer Recommendation Project I have analyzed beer ratings awarded by my husband who likes to try new beer each time he has the opportunity. I have recorded each beer already bought and currently we shop only for beers that are not in the file. Until now, 9.5% of all beers bought went down the drain because he didn’t like them. I have decided to build a machine learning model to predict ratings and shop only for those that get a predicted passing grade.

Beers are rated on a 1 to 10 scale where 1 is the worst score and 10 is the best, and a passing grade means 5 or higher. I have analyzed features that have influenced past ratings. After that, I have built three machine learning models that predict ratings of alcohol-free beer, light beer and regular beer. These models help with reducing costs by decreasing the number of discarded beer bottles.

This project proves there is a way to predict a numeric variable using one numeric feature and multiple categorical features as input. The numeric feature and the numeric target have a non-linear and non-monotonic relationship. Categorical data features influence the numeric target. Their influence is then predicted by machine learning models using a Distributed Random Forest tool from H2O.

Repository: https://github.com/alina-molnar/Beer-Recommendation-Project-Proof-of-Concept

Code file (Jupyter notebook), location on github: https://github.com/alina-molnar/Beer-Recommendation-Project-Proof-of-Concept/blob/main/beer_code.ipynb.

To run the code, open the Jupyter notebook file and click “Run All” button. Parts 1 to 5 will import the raw file and export all resulting files to output folder. Part 6 will import the file unseen when training models and will export results based on it.

Requirements file, location on github: ./Requirements.txt

Final Report, location on github: ./Final_Report.docx

PowerPoint Presentation, location on github: ./Summary_Presentation.pptx

Video Code Presentation, location on youtube: https://www.youtube.com/watch?v=0J-50p2U_wQ

Video Code Presentation, location on github: ./Video_Code_Presentation.mp4


Data used for training:
- input file: .xslx type on github: ./beer_input/
- output clean datasets: .csv type, location on github: ./beer_output/clean_files/
- output models: .zip type, location on github: ./beer_output/models/
- output variable importance: .csv type, location on github: ./beer_output/models/
- output predictions: .csv type, location on github: ./beer_output/predictions/
- output metrics: .csv type, location on github: ./beer_output/metrics/
- output false negatives: .csv type, location on github: ./beer_output/false_negatives/

Data used for test (files unseen by model when training):
- input unseen raw file: .csv type, location on github: ./unseen_data/unseen_input
- output unseen clean datasets: .csv type, location on github: ./unseen_data/unseen_output/unseen_clean
- output unseen predictions: .csv type, location on github: ./unseen_data/unseen_output/unseen_predictions
- output unseen metrics: .csv type, location on github: ./unseen_data/unseen_output/unseen_metrics
- output unseen false negatives: .csv type, location on github: ./unseen_data/unseen_output/unseen_false_negatives
