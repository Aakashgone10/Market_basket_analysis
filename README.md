# Market Basket Analysis using Apriori Algorithm

This project performs market basket analysis using the Apriori algorithm implemented with the `apyori` library. The goal is to generate frequent itemsets and association rules from transactional data, helping to identify relationships between items that frequently co-occur in transactions.

## Features

- **Frequent Itemset Generation**: Identifies sets of items that frequently appear together in transactions.
- **Association Rule Mining**: Discovers association rules that describe how the occurrence of one item is related to the occurrence of another.

## Parameters

The Apriori algorithm is configured with the following parameters:

- **Minimum Support (`min_sup`)**: The minimum proportion of transactions that must contain an itemset for it to be considered frequent.
- **Minimum Confidence (`min_conf`)**: The minimum confidence threshold for generating association rules.
- **Minimum Lift (`min_lift`)**: The minimum lift value for association rules, indicating the strength of a rule.
- **Minimum Length (`min_length`)**: The minimum number of items in an itemset to be considered for rule generation.

## Technologies Used

- **Python**: The primary programming language used for this analysis.
- **Pandas**: For data manipulation and preparation.
- **Apyori**: For implementing the Apriori algorithm.
- **Jupyter Notebook**: For interactive data analysis and visualization.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/market-basket-analysis.git
