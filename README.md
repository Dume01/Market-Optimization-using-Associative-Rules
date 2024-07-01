# Market-Optimization-using-Associative-Rules

This project implements the Apriori and Eclat algorithms for market basket optimization, a technique used in associative rule mining to discover interesting relationships between items in a customer's shopping basket.

## Apriori Algorithm

The Apriori algorithm is a classic algorithm used for finding frequent itemsets and association rules in a dataset. It operates by first identifying the frequent individual items in the dataset and then extending them to larger and larger itemsets as long as those itemsets appear sufficiently often in the dataset.

The Apriori algorithm is implemented in the `apriori.ipynb` notebook, which includes the following steps:

1. Importing the necessary libraries
2. Data preprocessing
3. Training the Apriori model on the dataset
4. Visualizing the results

The results are displayed in a Pandas DataFrame, sorted by descending lift values, which measure the strength of the association between the items in each rule.

## Eclat Algorithm

The Eclat (Equivalence Class Transformation) algorithm is another approach for finding frequent itemsets and association rules. Unlike Apriori, which operates in a breadth-first manner, Eclat uses a depth-first search approach, which can be more efficient for datasets with many frequent itemsets.

The Eclat algorithm is implemented in the `eclat.ipynb` notebook, following a similar structure to the Apriori implementation:

1. Importing the necessary libraries
2. Data preprocessing
3. Training the Eclat model on the dataset
4. Visualizing the results

The results are displayed in a Pandas DataFrame, sorted by descending support values, which measure the frequency of occurrence of each itemset in the dataset.

## Usage

To use these implementations, you'll need to have Python and the required libraries (NumPy, Pandas, Matplotlib, and Apyori) installed. The `Market_Basket_Optimisation.csv` file containing the transaction data should also be present in the same directory as the notebooks.

You can run the notebooks in an interactive environment like Jupyter Notebook or Google Colab. The notebooks include detailed explanations and comments to guide you through the code.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

