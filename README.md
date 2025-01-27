# Data Science Assignment: Zeotap

This repository contains the solutions for the Data Science assignment based on eCommerce transaction data. The tasks involve analyzing transaction data, building predictive models, and performing customer segmentation to derive actionable insights for the business.

---

## Project Overview
The assignment focuses on leveraging data science techniques to:
1. Perform **Exploratory Data Analysis (EDA)** to uncover trends and patterns in the data.
2. Build a **Lookalike Model** to recommend similar customers based on their profiles and transaction history.
3. Use **Customer Segmentation** techniques to cluster customers and analyze their behavior.

The datasets provided for this assignment include:
- **Customers.csv**: Information about customers, including their region and signup date.
- **Products.csv**: Product details such as category and price.
- **Transactions.csv**: Transaction details, including purchase quantities and total values.

---

## Tasks and Deliverables

### Task 1: Exploratory Data Analysis (EDA)
- **Objective**: Analyze the datasets to extract meaningful insights about customers, products, and transactions.
- **Key Insights**:
  1. Customers are unevenly distributed across regions, highlighting opportunities for targeted marketing in underrepresented regions.
  2. 'Electronics' and 'Books' are the most popular categories, indicating strong demand in these areas.
  3. Seasonal spikes in transactions reveal opportunities for optimizing promotional campaigns.
  4. Repeat customers drive significant revenue, emphasizing the importance of customer retention strategies.
  5. High average transaction value suggests opportunities for introducing premium product bundles.
- **Deliverables**:
  - Jupyter Notebook: `Anisha_Raj_EDA.ipynb`
  - PDF Report: `Anisha_Raj_EDA.pdf`

---

### Task 2: Lookalike Model
- **Objective**: Build a recommendation model to find 3 similar customers for each of the first 20 customers (`C0001` to `C0020`).
- **Details**:
  - The model uses cosine similarity based on customer transaction features (`Quantity`, `TotalValue`, and `ProductPrice`) and region encodings.
  - The output includes a similarity score for each recommendation.
- **Deliverables**:
  - Jupyter Notebook: `Anisha_Raj_Lookalike.ipynb`
  - CSV File: `Anisha_Raj_Lookalike.csv`

---

### Task 3: Customer Segmentation
- **Objective**: Segment customers into clusters using K-Means clustering.
- **Details**:
  - The optimal number of clusters is determined using the Davies-Bouldin Index.
  - Features used include transaction data (`Quantity`, `TotalValue`, and `ProductPrice`) and region encodings.
  - Visualizations of clusters are provided to analyze customer behavior.
- **Deliverables**:
  - Jupyter Notebook: `Anisha_Raj_Clustering.ipynb`
  - PDF Report: `Anisha_Raj_Clustering.pdf`
  - CSV File: `Anisha_Raj_Clustering.csv`

---

## Repository Structure
Here’s a breakdown of the repository files:

| File Name                     | Description                                                    |
|-------------------------------|----------------------------------------------------------------|
| `Anisha_Raj_EDA.ipynb`        | Jupyter Notebook containing the EDA and insights.             |
| `Anisha_Raj_EDA.pdf`          | PDF report summarizing the EDA and business insights.         |
| `Anisha_Raj_Lookalike.ipynb`  | Jupyter Notebook for the lookalike model.                     |
| `Anisha_Raj_Lookalike.csv`    | CSV file with the top 3 similar customers for the first 20 customers. |
| `Anisha_Raj_Clustering.ipynb` | Jupyter Notebook for customer segmentation.                   |
| `Anisha_Raj_Clustering.pdf`   | PDF report summarizing clustering results.                    |
| `Anisha_Raj_Clustering.csv`   | CSV file containing customer clusters and their assignments.  |

---

## How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/anishayh/data-science-assignment-zeotap.git
