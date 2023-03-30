# Home Credit Default Prediction

## Goals
1. I attempt to predict defaulters or non-defaulters using [Home Credit's Kaggle Dataset](https://www.kaggle.com/competitions/home-credit-default-risk/overview).
2. The model must quantify feature importance which appeals to domain knowledge.
3. I use the model to score Probability of Default (PD).
4. Use PD to compute Expected Loss of Principal Due to Default with 0% recovery rate.
5. Build a dashboard to address business questions related to Completed Cash Loans. See [link to dashboard](https://howeichin-ga-capstone-homecreditdashboard-home-9qwfal.streamlit.app/).

## Project Scopes
1. I considered approved cash loans only.  
2. Current applicants must have historical cash loans information from Home Credit.
3. Instalments for historical cash loans must be at most 3 years old.

## Jupyter Notebooks
Each notebook represents a step in the analytics process and there are 4 Jupyter Notebooks:
  1. columns-selection-for-selected-csv-files.ipynb: this notebook removes unused columns from the original dataset.
  2. duplicate-removal.ipynb: this notebook removes duplicates in the dataset.
  3. extracting-instalment-payment-features.ipynb: this notebook extracts features for downstream classification and completed cash loan data for analysis.
  4. default-prediction.ipynb: this notebook contains classification of defaulters or non-defaulters with logistic regression.

## Data links
I used Kaggle Notebook to run my code as it offers more computing power. Thus, I needed to upload the Home Credit datasets to Kaggle and store intermediate and final datasets there.

The following are links to the datasets I stored in Kaggle for my work:
  1. [raw-dataset](https://www.kaggle.com/datasets/wchohaw/raw-dataset): this link contains 4 csv files from Home Credit's original dataset.
  2. [intermediate-dataset](https://www.kaggle.com/datasets/wchohaw/intermediate-dataset): this link contains 3 csv files produced by columns-selection-for-selected-csv-files.ipynb and duplicate-removal.ipynb.
  3. [cleaned-dataset](https://www.kaggle.com/datasets/wchohaw/cleaned-dataset): this link contains 5 csv files produced by extracting-instalment-payment-features.ipynb.
