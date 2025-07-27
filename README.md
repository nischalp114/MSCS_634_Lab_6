# Association Rule Mining Lab (Book-Crossing Dataset)

**Name:** Nischal Pokharel  
**Course:** Advanced Big Data and Data Mining (MSCS-634-M40)  
**Lab Title:** Association Rule Mining with Apriori and FP-Growth

## Objective
The goal of this lab is to explore association rule mining techniques using the Apriori and FP-Growth algorithms. The Book-Crossing dataset is used to identify frequent itemsets and generate association rules based on user-book rating transactions.

## Dataset
- Source: Book-Crossing Dataset from Kaggle
- Files used:
  - BX-Book-Ratings.csv
  - BX-Books.csv
  - BX-Users.csv

## Summary of Work
- Cleaned and merged the dataset to create transaction data.
- Applied the Apriori algorithm to find frequent itemsets and generate rules.
- Applied the FP-Growth algorithm for comparison.
- Visualized results using Seaborn to highlight item frequencies and rule patterns.
- Compared the performance and output of Apriori vs. FP-Growth.

## Key Findings
- FP-Growth performed faster than Apriori on the same data.
- Meaningful book combinations were found with high confidence and lift values.
- Visualizations helped interpret strong associations and frequent items.

## Challenges
- The dataset was sparse, requiring filtering to reduce noise.
- Choosing appropriate support and confidence thresholds required experimentation.
- Some titles were long and difficult to display in visualizations.

## How to Run
1. Place the dataset CSV files in the same folder as the notebook.
2. Open and run `BookCrossing_Association_Mining.ipynb`.
3. Install any required libraries using pip if needed:
    ```
    pip install pandas matplotlib seaborn mlxtend
    ```
