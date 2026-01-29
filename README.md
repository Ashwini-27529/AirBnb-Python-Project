# 🏙️ Airbnb New York 2024 – Data Analysis using Python

## 📌 Project Overview

This project performs an **exploratory data analysis (EDA)** on the **Airbnb New York 2024 dataset** using Python. The goal is to analyze pricing patterns, neighborhood trends, and listing characteristics to derive meaningful insights that can help understand Airbnb market dynamics in New York City.

The analysis focuses on **data cleaning, feature engineering, aggregation, and insights generation**, making it a strong beginner-to-intermediate level data analytics project.

---

## 📂 Dataset

* **Source:** Airbnb New York Listings 2024
* **Format:** CSV
* **Records:** Multiple listings across NYC
* **Key Columns:**

  * `price`
  * `beds`, `bedrooms`, `baths`
  * `neighbourhood_group`, `neighbourhood`
  * `room_type`
  * `availability_365`
  * `number_of_reviews`, `rating`

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas** – data cleaning & manipulation
* **NumPy** – numerical operations
* **Jupyter Notebook** – analysis environment

---

## 🔍 Key Analysis Performed

### 1️⃣ Data Cleaning

* Converted numeric columns (`price`, `beds`) to appropriate data types
* Handled missing and invalid values
* Addressed zero-bed listings to avoid incorrect calculations

### 2️⃣ Feature Engineering

Created a new metric:

```python
price_per_bed = price / beds
```

This feature helps normalize listing prices and allows fair comparison across properties with different bed counts.

### 3️⃣ Aggregation & Grouping

* Calculated **average price per bed by neighbourhood group**
* Compared pricing trends across NYC boroughs

### 4️⃣ Exploratory Insights

* Manhattan listings have the **highest average price per bed**
* Brooklyn follows closely, indicating strong demand
* Staten Island and Bronx show comparatively lower pricing

---

## 📊 Sample Result

| Neighbourhood Group | Avg Price per Bed |
| ------------------- | ----------------- |
| Manhattan           | Highest           |
| Brooklyn            | High              |
| Queens              | Medium            |
| Bronx               | Low               |
| Staten Island       | Lowest            |

---

## 📈 Key Insights

* Location plays a **major role in pricing**
* Price-per-bed is a more reliable metric than raw price
* Central areas command premium rates even for smaller listings

---

## 🚀 How to Run the Project

#1. Clone the repository

   ```bash
   git clone https://github.com/Ashwini-27529/AirBnb-Python-Project.git
   ```

#2. Navigate to the project folder

   ```bash
   cd AirBnb-Python-Project
   ```

#3. Open the notebook

   ```bash
   jupyter notebook
   ```

#4. Run `AirBnb Python Project.ipynb`

---

## 📌 Project Highlights (Resume Ready)

* Performed end-to-end EDA on Airbnb NYC dataset using Python
* Engineered pricing metrics to enable fair comparison across listings
* Analyzed neighborhood-level pricing trends to extract business insights

---

## 📬 Contact

**Ashwini Shetty**
MCA Student | Aspiring Data Analyst
GitHub: [Ashwini-27529](https://github.com/Ashwini-27529)

---

⭐ If you like this project, don’t forget to star the repository!
