
 # Data Science Assignment: eCommerce Transactions Dataset


    ## Description
This project involves analyzing an eCommerce dataset containing customer, product, and transaction details. 
The tasks include:
- Exploratory Data Analysis (EDA)
- Building a Lookalike Model
- Customer Segmentation (Clustering)


   ## Dataset
The project uses the following datasets:
- **Customers.csv**: Contains customer details (e.g., `CustomerID`, `Region`, `SignupDate`).
- **Products.csv**: Contains product details (e.g., `ProductID`, `Category`, `Price`).
- **Transactions.csv**: Contains transaction details (e.g., `TransactionID`, `Quantity`, `TotalValue`).


4. Steps Implemented

   ## Steps Implemented
### Task 1: Exploratory Data Analysis (EDA)
- Cleaned and merged datasets.
- Visualized customer distribution, product popularity, and sales trends.
- Derived business insights (e.g., top-selling products and regions).

### Task 2: Lookalike Model
- Built a model to recommend 3 similar customers for the first 20 customers.
- Calculated similarity scores using cosine similarity.

### Task 3: Customer Segmentation
- Performed clustering using K-Means.
- Evaluated clusters with metrics such as the Davies-Bouldin Index and Silhouette Score.
- Visualized clusters using PCA.

5. Findings

   ## Findings
- **EDA Insights**:
  1. Most customers are from the `Asia` region.
  2. The top-selling product is `Product X`.
  3. Sales trends show consistent growth over time.

- **Lookalike Model**:
  - Recommended 3 similar customers for each of the first 20 customers.

- **Customer Segmentation**:
  - Optimal number of clusters: 4.
  - Davies-Bouldin Index: 0.72.
  - Silhouette Score: 0.61.

6. File Structure

   ## File Structure
- **FirstName_LastName_EDA.ipynb**: Jupyter Notebook for EDA.
- **FirstName_LastName_EDA.pdf**: PDF report of EDA insights.
- **FirstName_LastName_Lookalike.ipynb**: Jupyter Notebook for Lookalike Model.
- **FirstName_LastName_Lookalike.csv**: Results of Lookalike Model.
- **FirstName_LastName_Clustering.ipynb**: Jupyter Notebook for Clustering.
- **FirstName_LastName_Clustering.pdf**: PDF report of clustering results.

7. How to Run the Code

   ## How to Run the Code
   Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/YourRepoName.git
   ```
   Install the required Python libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
  Run the Jupyter Notebook files in the following order:
   - **FirstName_LastName_EDA.ipynb**
   - **FirstName_LastName_Lookalike.ipynb**
   - **FirstName_LastName_Clustering.ipynb**
   Check the generated output files for results.

