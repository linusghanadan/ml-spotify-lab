# Building predictive user classification model with data from Spotify API

## Background
These models were originally built for an assignment in my machine learning class. For the assignment, I built four different types of decision tree models that predict whether a given song was in my Spotify collection or in the collection my classmate Maxwell. Then, I compared performance across the four models. Specifically, I compare the performance of models built using a single decision tree, bagged decision trees, a random forest, and Stochastic Gradient Boosting (SGB).

## Repository contents
    ml-spotify-lab
    └───data
        │   My liked songs data (from Spotfiy API): linus_tracks.csv
        │   Maxwell's liked songs data (from Spotify API): maxwell_tracks.csv
    └───images
        │   Combined plot of the four confusion matrices (one for each model): plot-1.png
        │   Plot of accuracy and ROC AUC for each model: plot-2.png
        │   Plot of sensitivity and specificity for each model: plot-3.png
        │   Feature importance plot for SGB model: plot-4.png
    │   README.md
    │   .Rmd
    │   .Rproj
