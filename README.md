# N-Gram Analysis for Financial News Sentiment

This repository contains a Jupyter Notebook (`FinancialNews_Ngram_Assignment.ipynb`) for performing n-gram analysis on the Sentiment Analysis for Financial News dataset from Kaggle. The analysis includes generating unigrams, bigrams, and trigrams, training n-gram models, applying Laplace smoothing, implementing linear interpolation, and evaluating model performance using perplexity. The results are visualized in figures saved to the `Results/` folder.

## Repository Structure

- `FinancialNews_Ngram_Assignment.ipynb`: Jupyter Notebook containing the main code for n-gram analysis.
- `dataset/all-data.csv`: Dataset containing two columns.
- `Results/`: Folder where output figures are saved:
  - `unigram_mostfrequent_.pdf`: Top 10 unigrams.
  - `bigram_mostfrequent_.pdf`: Top 10 bigrams.
  - `triigram_mostfrequent_.pdf`: Top 10 trigrams.
  - `comparison_among_unsmoothed_.pdf`: Perplexity of unsmoothed models.
  - `comparison_among_smoothed_Unsmoothed_.pdf`: Unsmoothed vs. Laplace-smoothed perplexity.
  - `comparison_all_.pdf`: Perplexity across model types (Normal, Smoothed, Interpolated).


## Dependencies

To run the Jupyter Notebook, you need the following Python packages:
- `python>=3.8`
- `jupyter`
- `pandas>=1.5.0`
- `numpy>=1.23.0`
- `matplotlib>=3.5.0`
- `seaborn>=0.12.0`


 ## Setup Instructions

 1. **Clone the Repository**:
   ```bash
   git clone https://github.com/kcnishan/NLP_sentiment_Assignment.git
   cd NLP_sentiment_Assignment
```


 2. Install Python Dependencies: Create a virtual environment and install the required packages:


 3. Prepare the Dataset: Ensure the dataset is located at dataset/all-data.csv. The file should contain a text column with financial news headlines. 

 4. Running the Code

  - Launch Jupyter Notebook

  - Run the Notebook






