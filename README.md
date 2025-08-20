# -Customer-Segmentation-Analysis-on-Brazilian-Olist-Dataset
A data-driven RFM segmentation revealing customer behavior, loyalty patterns, and strategic insights for e-commerce growth.
# Customer Segmentation Analysis on Brazilian Olist Dataset

## Project Overview

This project focuses on applying customer segmentation techniques to the Brazilian Olist E-commerce Public Dataset. The primary goal is to categorize customers into distinct behavioral groups based on their purchasing habits, using the RFM (Recency, Frequency, Monetary) model. This analysis provides actionable insights for targeted marketing strategies, customer retention efforts, and personalized customer experiences.

## Dataset

The dataset used in this project is the **Brazilian Olist E-commerce Public Dataset**. It contains information on 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. It includes various details about orders, customers, products, sellers, and payments.

## Methodology

This project utilizes the **RFM (Recency, Frequency, Monetary) analysis** technique for customer segmentation.

*   **Recency:** How recently did the customer make a purchase? (Lower value indicates more recent activity)
*   **Frequency:** How often does the customer make purchases? (Higher value indicates more frequent purchases)
*   **Monetary:** How much money does the customer spend? (Higher value indicates higher spending)

The process involved:
1.  **Data Preprocessing:** Cleaning and preparing the raw Olist dataset for RFM calculation.
2.  **RFM Calculation:** Computing Recency, Frequency, and Monetary values for each customer.
3.  **RFM Scoring:** Assigning scores (e.g., 1-5) to each RFM metric based on quantiles.
4.  **Customer Segmentation:** Grouping customers into well-defined segments (e.g., Champions, Loyal Customers, At Risk, Lost Customers) based on their combined RFM scores.
5.  **Segment Analysis:** Analyzing the characteristics and preferences of each segment.

## Key Findings and Customer Segments

The analysis revealed several distinct customer segments, each with unique characteristics and requiring tailored engagement strategies:

*   **Champions:** Our best customers, who buy recently, frequently, and spend the most. These customers are highly valuable and should be rewarded to maintain loyalty.
*   **Loyal Customers:** Customers who buy frequently and spend a good amount. They are responsive to promotions and are less likely to churn.
*   **Potential Loyalists:** Recent customers who have bought frequently but haven't spent much yet. They have the potential to become loyal customers.
*   **New Customers:** Customers who have made a very recent purchase but haven't purchased frequently or spent much. They need to be nurtured to encourage repeat business.
*   **At Risk:** Customers who used to buy frequently and spent good money but haven't purchased recently. These customers are at risk of churning and require re-engagement efforts.
*   **Cannot Lose Them:** Customers who bought big and often but haven't returned for a long time. These are valuable customers who need strong win-back strategies.
*   **Lost Customers:** Customers who haven't purchased for a long time, bought few times, and spent little. It might be challenging to win them back, but targeted campaigns could be explored.

**(Optional: If you have visualizations, you can describe them here or add screenshots if this README will live in the repo with images)**
*   Visualizations were created to show the distribution of customers across segments, average RFM scores per segment, and product category preferences for different segments.

## Actionable Insights and Recommendations

Based on the segmentation, the following strategic recommendations can be made for Olist:

*   **Reward Champions:** Implement exclusive loyalty programs, early access to new products, or personalized offers to maintain their high engagement.
*   **Re-engage At Risk Customers:** Send personalized re-engagement campaigns, special discounts, or surveys to understand their changing needs.
*   **Win Back Lost Customers:** Develop targeted campaigns with significant incentives to encourage a return, focusing on products they previously favored.
*   **Nurture New Customers:** Provide excellent onboarding experiences, follow-up communications, and small incentives for their next purchase.
*   **Tailor Product Offerings:** Use segment-specific product preferences (e.g., Champions favoring home & wellness, New Customers exploring entry-level categories) to optimize product recommendations.
*   **Geographical Targeting:** Utilize insights into the geographical distribution of segments (e.g., concentration of Lost Customers in specific states) for localized marketing initiatives.

## Technologies Used

*   **Python**
*   **Pandas:** For data manipulation and analysis.
*   **NumPy:** For numerical operations.
*   **Matplotlib:** For data visualization.
*   **Seaborn:** For enhanced data visualization.
*   **Jupyter Notebook:** For interactive development and analysis.

## How to Run the Project (Local Setup)

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash  
    git clone https://github.com/YourUsername/your-repo-name.git  
    cd your-repo-name
2. Create a virtual environment
   python -m venv venv  
source venv/bin/activate  # On Windows: `venv\Scripts\activate`
3. Install the required libraries:
   pip install pandas numpy matplotlib seaborn jupyter
4. Download the dataset: (If the dataset is too large to include in the repo, provide instructions or a link to where it can be downloaded, e.g., Kaggle.) You can download the Olist E-commerce Public Dataset from Kaggle. Place the unzipped CSV files into a data/ directory within your project.
5. Run the Jupyter Notebook:
  jupyter notebook "Customer segmentation analysis on brazilian Olist dataset - Jupyter Notebook.ipynb"
This will open the notebook in your web browser, where you can execute the cells to see the analysis.


 
