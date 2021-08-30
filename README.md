# Beer-Recommendation-Project-Proof-of-Concept
Beer Recommendation Project (Proof of Concept)
ML models with H2O for predicting customer's preference using past ratings

The goal of this project is to predict customer’s ratings of new beer using past preferences. Features that describe past ratings are mainly categorical data (e.g. beer style, beer flavor). Alcohol content was stored as numeric data and used together with the categoricals to generate a prediction model.

This project was intended to prove there is a way to predict a numeric variable using one numeric feature and multiple categorical features as input. The numeric feature and the numeric target had a non-linear and non-monotonic relationship. The categorical features don’t require previous encoding.

To run the code, open the Jupyter notebook file and press the “Run All” button. If your computer can’t process it all at once, run steps 1-3 initially (by scrolling to the first code cell in step 4 and pressing “Execute Above Cells”). After it finishes running, run steps 4-5 (by staying in the first code cell in step 4 and pressing “Execute Cell and Below”).

All files are stored in folders based on input/output classification.

Repository: https://github.com/alina-molnar/Beer-Recommendation-Project-Proof-of-Concept

Code file (Jupyter notebook) on github: https://github.com/alina-molnar/Beer-Recommendation-Project-Proof-of-Concept/blob/main/beer_code.ipynb

Final Report on github: https://github.com/alina-molnar/Beer-Recommendation-Project-Proof-of-Concept/blob/main/Final-Report.docx

Input file is .xslx type on github: ./beer_input/

Output files are:
•	clean datasets: .csv type on github: ./beer_output/cleaning_output/
•	models: .zip type on github: ./beer_output/models/
•	predictions: .csv type on github: ./beer_output/predictions/
•	metrics: .csv type on github: ./beer_output/metrics/
•	false negatives: .csv type on github: ./beer_output/false_negatives/
