# Airbnb Price Analysis for Albany, NY

This project is an exploratory data analysis of the public Airbnb dataset for Albany, NY. The goal is to practice data cleaning, analysis, and visualization to uncover patterns in pricing, availability, and listing distribution across the city.

**Tech Stack:** Python, Pandas, Plotly, Jupyter Notebook



---

## Key Questions Answered

This analysis seeks to answer the following questions:
1.  What is the distribution of listings across different Albany neighborhoods?
2.  How do prices vary by neighborhood and room type?
3.  Is there a geographical pattern to pricing and listing availability?
4.  What is the relationship between a listing's price and its number of reviews?

---

## Key Findings

* **Price and Location:** The most expensive listings are concentrated in specific downtown neighborhoods. Prices for "Entire home/apt" listings are significantly higher on average than private or shared rooms.
* **Listing Distribution:** Certain neighborhoods contain a much higher density of listings than others, indicating popular areas for visitors.
* **Price and Reviews:** There appears to be no significant statistical correlation between the price of a listing and the number of reviews it has received.

---

## Setup & Usage

To replicate this analysis, clone the repository and install the required libraries.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/turganaliev/airbnb-albany-analysis.git
    cd airbnb-albany-analysis
    ```
2.  **Create a virtual environment and install dependencies:**
    ```bash
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```
3.  **Run the Analysis:**
    The full analysis is contained within the `albany_analysis.ipynb` Jupyter Notebook.
