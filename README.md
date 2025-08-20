# -Customer-Segmentation-Analysis-on-Brazilian-Olist-Dataset
A data-driven RFM segmentation revealing customer behavior, loyalty patterns, and strategic insights for e-commerce growth.
#
## 🧠 Overview

This project applies the RFM (Recency, Frequency, Monetary) model to segment customers from the Brazilian Olist e-commerce platform. By analyzing purchasing behavior, product preferences, and geographic trends, the project uncovers actionable insights to drive retention, loyalty, and strategic growth.

---

## 🧪 Methodology

### 1️⃣ Data Loading & Merging  
- Imported five datasets: orders, customers, items, products, and category translations  
- Merged them into a unified DataFrame for holistic customer analysis

### 2️⃣ Data Cleaning & Preparation  
- Converted timestamps to datetime format  
- Checked and handled missing values  
- Calculated total revenue per order

### 3️⃣ RFM Metric Calculation  
- Defined a snapshot date (one day after the last purchase)  
- Computed:
  - **Recency**: Days since last purchase  
  - **Frequency**: Number of orders  
  - **Monetary**: Total spend

### 4️⃣ Exploratory Data Analysis (EDA)  
- Visualized distributions of Recency, Frequency, and Monetary  
- Identified skewness, outliers, and behavioral patterns

### 5️⃣ Customer Segmentation  
- Assigned RFM scores using quintiles  
- Mapped score combinations to intuitive segments:
  - Champions
  - Loyal Customers
  - Potential Loyalists
  - New Customers
  - At Risk
  - Lost Customers
  - Others

### 6️⃣ Segment Profiling  
- Compared average RFM metrics across segments  
- Visualized segment proportions, profiles, and behavioral clusters

---

## 📈 Key Visuals

- Bar Chart: Average RFM metrics per segment  
- Pie Chart: Segment distribution  
- Radar Chart: Normalized segment profiles  
- Scatterplot: Frequency vs. Monetary by segment  
- Heatmap: Segment performance across RFM metrics  
- Category Analysis: Top products by purchase count and spend  
- Geographic Heatmap: Segment distribution across Brazilian states  
- Trend Line: Monthly segment evolution

---

## 💡 Strategic Insights

### Segment Behavior
- **Champions**: Recent, frequent, high spenders—ideal for loyalty programs  
- **At Risk**: High historical spend but poor recency—prime for reactivation  
- **Lost Customers**: Long inactive, low value—target with win-back campaigns  
- **New Customers**: Recent but infrequent—need onboarding and nurturing  
- **Potential Loyalists**: Moderate scores—ready for upselling

### Product Preferences
- Champions and Loyal Customers favor home and wellness categories  
- Lost Customers previously bought similar items—suggesting re-engagement potential  
- New Customers explore entry-level categories—ideal for introductory promotions  
- Potential Loyalists lean toward productivity-related products

### Geographic Trends
- Lost Customers cluster in São Paulo (SP), Rio de Janeiro (RJ), and Minas Gerais (MG)  
- Champions are geographically diverse—value exists beyond urban centers  
- Regional segmentation supports localized marketing and inventory planning

### Behavioral Trends
- Segment sizes fluctuate monthly  
- Promotions drive spikes in New Customers  
- Engagement drops correlate with churn

---

## 🎯 Recommendations

- **Retention Focus**: Prioritize At Risk and Potential Loyalists with personalized offers  
- **Loyalty Programs**: Reward Champions to maintain engagement  
- **Win-Back Campaigns**: Target Lost Customers in SP, RJ, and MG  
- **Product Strategy**: Align inventory with segment-specific preferences  
- **Regional Marketing**: Customize outreach based on geographic insights

---

## 🗣️ Personal Reflection

This project taught me how to turn raw transactional data into strategic insights. I deepened my skills in customer analytics, data storytelling, and visual communication. It’s a perfect example of how data science can bridge the gap between numbers and business impact.


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


 
