# ✈️ Flying Happy — Airline Passenger Satisfaction Dashboard

An **interactive Streamlit dashboard** for analyzing airline passenger satisfaction. Explore passenger demographics, service ratings, and flight operations using **Plotly** visualizations.  

**Live demo image:**

![Dashboard Preview](https://www.elliott.org/wp-content/uploads/No-Room.png)

---

## Features

### 1️⃣ Overview & Demographics
- Pie chart of overall passenger satisfaction.
- Line charts comparing satisfaction across:
  - Age groups
  - Class (Economy, Business, etc.)
  - Gender
  - Customer type (Loyalty, One-time)
- Shows filtered row count dynamically.

### 2️⃣ Service Ratings
- Correlation heatmap of service ratings.
- Bar chart highlighting services that most strongly drive satisfaction.

### 3️⃣ Flight Operations
- Box plots of departure and arrival delays by satisfaction.
- Histograms for travel type vs satisfaction.
- Provides conclusions and recommendations for improvement.

### 4️⃣ Sidebar Filters
- Class
- Customer type
- Travel type
- Gender
- Age range
- Gradient-styled sidebar for improved UI experience.

---

## Dataset

- **Source:** [Kaggle - Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)  
- **Expected CSV:** `airline_passenger_satisfaction.csv`  
- Columns are automatically normalized (lowercase, underscores, trimmed spaces).

---

## Installation & Running Locally

1. Clone the repository or download the script.
2. Install required dependencies:

```bash
pip install -r requirements.txt
