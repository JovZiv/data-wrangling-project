# Barcelona Short-Term Rental Performance 🏙️

## Project Overview

This project analyses Airbnb rental performance in Barcelona to explore neighbourhood differences, pricing, weather, tourism, and seasonality.

## 🎯 Business Objective

Support a short-term rental operator considering expansion into Barcelona by identifying factors associated with rental performance and informing property selection and pricing decisions.

## 🔍 Research Questions

* **H1 — Location:** How does performance vary across neighbourhoods, and does proximity to transport and attractions matter?
* **H2 — Pricing:** Is a higher nightly rate associated with lower occupancy?
* **H3 — Weather & Tourism:** Are weather and tourism conditions associated with occupancy?
* **H4 — Seasonality:** How does rental performance change throughout the year?

## 📊 Key Findings

* **Location:** Eixample led in financial performance, while Gràcia had the highest occupancy in the analysed dataset.
* **Proximity:** Metro proximity and tourist-attraction density showed weak relationships with rental performance.
* **Pricing:** Higher nightly rates were not consistently associated with lower occupancy.
* **Weather:** Temperature and sunshine showed positive correlations with occupancy.
* **Seasonality:** Occupancy and RevPAR peaked during the summer and were lowest in January.

## 🛠️ Tools & Technologies

* Python
* Pandas
* Jupyter Notebook
* Data analysis & visualisation
* APIs and external datasets

## 📁 Repository Structure

```text
data-wrangling-project/
│
├── 1_airbnb_wrangling.ipynb
├── 2_ine_wrangling.ipynb
├── 3_poi_wrangling.ipynb
├── 4_weather_wrangling.ipynb
│
├── airbnb_final.csv
├── ine_final.csv
├── poi_final.csv
├── weather_final.csv
│
├── h1_location_vs_rental_performance.ipynb
├── h2_price_vs_occupancy.ipynb
├── h3_weather.ipynb
└── h4_seasonality.ipynb
```

* **Wrangling notebooks:** Clean and prepare the Airbnb, INE tourism, POI, and weather datasets.
* **Hypothesis notebooks:** Analyse the four research questions.
* **Final CSV files:** Contain the processed datasets used in the analysis.

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/JovZiv/data-wrangling-project.git
cd data-wrangling-project
```

### 💻 Using VS Code

Open the project folder in **VS Code** and select any `.ipynb` notebook.

### 📓 Using Jupyter Notebook

From the project folder, run:

```bash
jupyter notebook
```

Then select the notebook you want to open.

## 📚 Data Sources

* **Kaggle** — Airbnb listings and rental performance
* **Open-Meteo** — Historical weather data
* **INE Spain** — Tourism statistics
* **OpenStreetMap / Geoapify** — Geographic information and points of interest

## ⚠️ Limitations

This analysis identifies associations, not causation. Findings are limited to the available dataset and the variables measured, and may not represent every Airbnb listing in Barcelona.

## 👥 Project Information

**Course:** Ironhack Data Analytics Bootcamp  
**Project:** Barcelona Short-Term Rental Performance  
**Team:** Team Berlin — Jovana Zivkovic & Yurii Slobodchukov

