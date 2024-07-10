## Pet Product Sales Analysis - Certification Project
**Description:**

This repository contains the file, code and visualizations used to analyze a pet product sales dataset for Datacamp certification project.

The original dataset contained 879 rows and 9 columns. The data cleaning process involved the following steps documented in the script data_cleaning.py:

Sales Column: Converted to a numeric data type by removing commas and dollar signs.
Pet Type: Rows containing pet types other than dogs, cats, fish, and birds were removed (46 rows).
Duplicates & Missing Values: Scripts checked for and confirmed no duplicate rows or missing values exist.
The cleaned dataset with 833 rows has the following characteristics:

Product Identifiers: 879 unique product IDs.
Product Categories: 11 categories.
Pet Sizes: 5 sizes.
Pet Types: 4 types (dog, cat, fish, bird).
Rating: 10-point scale.
Rebuy: Binary (1 or 0).
Data Discovery & Visualization

## Analysis Findings

This section explores customer purchase behavior and product popularity to inform marketing strategies.

**Repurchase Frequency:**

* **Total Repurchases:** 390 products were purchased more than once.
* **Top Repurchased Categories:** Equipment, Snacks, and Toys.

**Repurchase vs. Sales:**

* **Total Sales - Once Purchased:** $51,125,000 (higher)
* **Total Sales - Repurchased:** $45,587,000 (lower)
* **Average Sale - Repurchased:** Higher than once purchased products.
* **High Total Sales - Once Purchased:** Snacks, Toys, Supplements (potentially due to higher price points).

**Repurchase by Pet Type:**

* **Dogs & Cats:** Equipment, Food, Medicine, Toys, Snacks (more likely repurchased).
* **Fish:** Equipment, Snacks, Toys (more likely repurchased).
* **Birds:** Equipment, Toys, Snacks (more likely repurchased).

**Recommendations:**

* **Subscription List:** Include Equipment, Toys, and Snack products based on high repurchase rates.
* **Marketing Focus:** Target Cats & Dogs due to higher sales and purchase volume.
* **Further Research:** Investigate customer preferences and repurchase factors.
* **Subscription List (Once Purchased):** Consider including specific high-selling, once-purchased products.

**Conclusion:**

Equipment, Toys, and Snack products are popular across purchase types (once & repurchased) and should be prioritized for subscription lists. Cats & Dogs represent a key customer segment. Further research on customer preferences and repurchase behavior is recommended. Interestingly, some high-selling products are only purchased once, suggesting they might also be valuable additions to the subscription list.  


Tools Used:

(Replace with the specific tools you used for analysis and visualization)

Programming Language (e.g., Python)
Data Analysis Library (e.g., pandas)
Visualization Library (e.g., matplotlib, seaborn)
