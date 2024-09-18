# Predicting-Building-Types-Using-OpenStreetMap
This project classifies buildings in Bhopal, India, as residential or non-residential using OpenStreetMap (OSM) data. The Bhopal data was collected and processed by our team, while the Boulder, Colorado, dataset served as the base paper for model adaptation and validation. The Bhopal City data used is private and is available on request.

Key Features:

Data collection, preprocessing, and feature engineering for Bhopal city using PyOsmium and Geopandas.
Features like proximity to roads, intersection with land use, and building footprint size were used for classification.
Implemented a C4.5 decision tree model, achieving 86% accuracy on the Bhopal dataset.
Technologies: Python, PyOsmium, Geopandas, Scikit-learn, OpenStreetMap API.

Results: Bhopal: Accuracy 86%, F1-score 0.78. Boulder (base study replication): Accuracy 96%, F1-score 0.89.

Limitations: The model’s adaptability requires retraining for datasets with different OSM attributes.

This clarifies your contribution in Bhopal and the usage of Boulder as the reference dataset.
