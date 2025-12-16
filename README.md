# SHL-Intern-Hiring-Assessment-2025
Grammar Scoring Engine – SHL Hiring Assessment
Overview

This project builds a grammar scoring engine for spoken audio samples.
The system predicts a grammar score between 0 and 5 from speech recordings.

The solution was developed as part of the SHL Intern Hiring Assessment.

Problem Statement

Given an audio file (45–60 seconds long), predict the grammar quality of the speaker using a continuous score from 0 to 5.

Approach

Extracted acoustic and fluency-based speech features directly from audio files.

Features include:

MFCCs

Energy and zero-crossing rate

Spectral centroid and bandwidth

Duration-related features

Trained a Random Forest regression model to predict grammar scores.

Evaluated the model using RMSE and Pearson correlation.

Due to restricted internet access, speech-to-text was not used.

Results

Training RMSE: ~0.27

Validation RMSE: ~0.67

Validation Pearson Correlation: ~0.51

Kaggle Leaderboard Pearson Correlation: ~0.91

These results show that speech patterns and acoustic features can effectively reflect grammatical proficiency.

Files

grammar-scoring-engine.ipynb – Main notebook containing code, evaluation, and visualizations

README.md – Project description

⚠️ Audio data is not included, as per competition rules.

How to Run:

Open the notebook in Kaggle.

Attach the SHL Intern Hiring Assessment dataset.

Run the notebook from top to bottom.

Notes

This project uses offline audio feature extraction.

Text-based grammar analysis can be added in future using speech-to-text.

Author

Lohitha Earlapati
