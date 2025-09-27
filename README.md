#Thyroid-Cancer-Recurrence Predictor


This project turns raw clinical check-ups into a crystal-ball forecast: feed it a patient’s age, gender, smoking status, tumour stage, treatment response, etc., and it instantly returns the probability that thyroid cancer will come back.
We cleaned 900+ records, trained a Random-Forest model (ROC-AUC ≈ 0.94), wrapped it in an interactive CLI, and packed everything into a single Colab-ready repo for anyone to reuse or extend.

What's inside:

||File	==> Purpose||
||dataset.csv	==> 900+ patient records used for training||
||ThyroidCancer.ipynb	==> End-to-end Colab notebook (EDA → modelling → evaluation)||
||Thyroid Cancer Detection.pdf ==> About the project and dataset||
||thyroid_recurrence_model.pkl ==> Trained Random-Forest model||
