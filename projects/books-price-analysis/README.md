# Books Price Analysis using Python (Web Scraping + EDA)

## Project Overview

This project demonstrates how to scrape book data from the **Books to Scrape** website using Python and perform exploratory data analysis (EDA).

The project covers the complete data analysis workflow:

* Web scraping using BeautifulSoup
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* Extracting business insights
* Exporting the cleaned dataset

---

## Project Objectives

* Scrape book information from all 50 pages of the website
* Clean and preprocess the collected data
* Analyze book prices and ratings
* Visualize important trends
* Generate meaningful insights from the dataset

---

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Dataset

Source:
**Books to Scrape**
[https://books.toscrape.com/](https://books.toscrape.com/)

The final dataset contains **1,000 books**.

### Features

* Title
* Price (£)
* Rating
* Availability
* Price Category

---

## Project Workflow

### 1. Web Scraping

* Connected to the website using `requests`
* Parsed HTML using BeautifulSoup
* Extracted:

  * Book Title
  * Price
  * Rating
  * Availability
* Scraped data from all **50 pages**

---

### 2. Data Cleaning

* Converted prices to numeric values
* Converted text ratings (One, Two, Three...) into numerical ratings (1–5)
* Checked for:

  * Missing values
  * Duplicate records
* Verified data types

---

### 3. Exploratory Data Analysis

Performed analyses including:

* Summary statistics
* Rating distribution
* Price distribution
* Top 10 most expensive books
* Average price by rating
* Price category analysis
* Correlation between price and rating

---

## Visualizations

The project includes the following charts:

* Rating Distribution
* Price Distribution (Histogram)
* Top 10 Most Expensive Books
* Average Price by Rating
* Price Category Distribution
* Box Plot of Book Prices
* Scatter Plot (Price vs Rating)

---

## Key Insights

* Successfully scraped **1,000 books** from all 50 pages.
* Book ratings range from **1 to 5 stars**.
* Prices vary across a wide range, indicating different pricing segments.
* Most books fall into the **Low** and **Medium** price categories.
* Five-star books are available across multiple price ranges rather than only at premium prices.
* The correlation between **price and rating is weak**, suggesting higher-priced books do not necessarily receive better ratings.
* The dataset contains **no missing values or duplicate records** after preprocessing.

---

## Project Structure

```
Books-Price-Analysis/
│
├── README.md
├── Books Price Analysis.ipynb
├── books_analysis_final.csv
└──charts/
   ├── Rating Distribution.png
   ├── Distribution of Book Prices.png
   ├── Top 10 Most Expensive Books.png
   ├── Average Price by Rating.png
   ├── Box Plot of Book Prices.png
   ├── Books by Price Category.png
   └── Price vs Rating.png

```

---

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/Books-Price-Analysis.git
```

2. Install dependencies.

```bash
pip install pandas matplotlib requests beautifulsoup4
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells to scrape the data, perform analysis, and generate visualizations.

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Web scraping with BeautifulSoup
* Data collection from websites
* Data cleaning using Pandas
* Exploratory Data Analysis (EDA)
* Data visualization with Matplotlib
* Extracting actionable insights from real-world datasets

---

## Author

**Yash Agrawal**

If you found this project helpful, feel free to give star to the repository.
