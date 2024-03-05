# Textual Analysis of Amazon Review - Electronics (Camera & Accessories) 
## Research Project of Text Mining for Economics and Finance

This repository contains notebooks for various stages of our research project: https://github.com/RANN9/Amazon-Review-TMEF-Project

- `data_preprocessing_final.ipynb`: convert raw JSON files to CSV format, remove non-useful columns, and prepare the data for further analysis
- `data_normalisation_final.ipynb`: implement robust text normalisation techniques and remove entities which could potentially bias our analysis
- `exploratory_data_analysis_final.ipynb`: conduct exploratory data analysis to gain insights into the dataset's characteristics and distribution
- `complexity_and_similarity_final.ipynb`: calculate language complexity, diversity and similarity of review text to uncover linguistic patterns and intertemporal shift in linguistic patterns
- `predictive_modelling_final.ipynb`: utilises various models to predict ratings based on review text; discover intertemporal changes in review text
- `sentiment_variance_final.ipynb`: investigate the variance in review sentiment across different rating levels

Dataset:
- `review.csv`: preprocessed review dataset
- `product.csv`: preprocessed product dataset
- `review_camera_normalised.csv`: normalised and preprocessed camera product dataset
- `review_subset_normalised.csv`: normalised and preprocessed data subset of all electronics products (we have only normalised a subset of the entire electronics product dataset as it is already sufficient for our analysis)
- Link of preprocessed and normalised data: https://drive.google.com/drive/folders/1iABJWKwf3jHczTkWaAGC0amdwKFyXOYH?usp=drive_link

Original Dataset:
- Link of original dataset: https://nijianmo.github.io/amazon/index.html

