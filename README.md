# Amazon Sales Data Analysis

This project analyzes an Amazon sales dataset to explore product ratings, pricing, and customer behavior. It demonstrates key data science skills, including data loading, cleaning, analysis, visualization, and storytelling using Python and popular libraries such as pandas, matplotlib, seaborn, and Streamlit.

---

## Project Overview

The dataset contains information on over 1,400 Amazon products, including details like product categories, pricing, ratings, and customer reviews. The main objectives of this project are to:

- Clean and prepare the data for analysis.
- Perform basic statistical analysis to uncover insights.
- Visualize trends and relationships in the data.
- Segment customers based on their rating behavior.
- Assess the impact of review length on product engagement.

The analysis is presented both in a Jupyter notebook for detailed exploration and in an interactive Streamlit app to tell a compelling data story.

---

## Dataset

- **Source:** The dataset is a CSV file (`amazon_sales.csv`) with 1,465 entries and 16 columns, including:
  - `product_id`, `product_name`, `category`
  - `discounted_price`, `actual_price`, `discount_percentage`
  - `rating`, `rating_count`
  - `about_product`, `user_id`, `user_name`, `review_id`, `review_title`, `review_content`
  - `img_link`, `product_link`

- **Data Types:**  
  Initially loaded as strings, with numerical columns cleaned and converted for analysis.

- **Missing Values:**  
  Addressed by filling or dropping as appropriate (e.g., using median for ratings and 0 for rating counts).

---

## Project Structure


- **data/**: Contains the raw dataset.
- **notebooks/**: Houses the Jupyter notebook with step-by-step analysis, including data cleaning, statistics, and visualizations.
- **scripts/**: Includes the Streamlit app script for an interactive dashboard.
- **images/**: (Optional) Stores visualizations for reports or presentations.
- **README.md**: This file, providing a project overview and setup guide.
- **requirements.txt**: Lists Python dependencies for easy installation.

---

## Setup Instructions

### Clone the Repository

```bash
git clone https://github.com/yourusername/amazon-sales-analysis.git
cd amazon-sales-analysis

### install Dependancies
'''bash 
pip install -r requirements.txt

# Running the Jupyter Notebook

Open `notebooks/analysis2.ipynb` in Jupyter to explore the detailed analysis.

Launch the environment with one of the following commands:

```bash
jupyter notebook

# Running the Streamlit App

Execute the following command to launch the interactive dashboard:

```bash
streamlit run scripts/app.py

