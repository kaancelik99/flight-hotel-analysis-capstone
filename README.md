# ✈️ Flight Delays vs. Hotel Quality by City

This capstone project explores the relationship between flight delays and hotel infrastructure across major U.S. cities using two public datasets from Kaggle. The goal is to determine whether frequent flight delays are associated with higher hotel availability, pricing, or quality, offering insights for travelers and tourism planners.

## 📊 Tools Used
- Python (Pandas) for data cleaning and preparation
- SQL (PostgreSQL/SQLite) for joining and querying datasets
- Tableau for interactive data visualization

## 📁 Datasets
1. **Flight Delay Dataset (2018–2022)**  
   [Kaggle Link](https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022)  
   Includes flight origin, destination, delays, and cancellation details.

2. **Hotel Dataset**  
   [Kaggle Link](https://www.kaggle.com/datasets/raj713335/tbo-hotels-dataset)  
   Includes hotel names, star ratings, prices, and cities.

3. **Airport to City Mapping**  
   Used to link airport codes (IATA) to city names for data joining.

## 📂 Project Structure


flight-hotel-analysis-capstone/
├── data/
│ ├── flights.csv
│ ├── hotels.csv
│ └── airport_city_mapping.csv
├── notebooks/
│ └── data_cleaning_joining.ipynb
├── sql/
│ └── join_flight_hotel.sql
├── tableau/
│ └── dashboard_mockup.twb
├── README.md
└── requirements.txt


## 🧹 Key Tasks
- Cleaned and standardized city names, delay columns, and hotel data
- Joined datasets on city names via airport-city mapping
- Aggregated metrics like average delay, hotel price, and star rating per city

## 🔍 Analytical Questions Explored
- Which cities have the worst flight delays and what hotel options do they offer?
- Do cities with more delays tend to have higher hotel prices?
- Is there a correlation between hotel quality and average departure delays?

## 📈 Tableau Dashboard Highlights
- Top cities by delay vs. hotel quality
- Heatmap of hotel pricing across cities
- Interactive filters by city, star rating, and delay level

## 📌 Future Work
- Time-series breakdown of delay trends
- Integrate weather data for deeper delay cause analysis
- Explore airport-specific hotel partnerships or discounts

## 👨‍💻 Author
Salim Kaan Celik – [LinkedIn](https://www.linkedin.com/in/kaancelik1/) | [GitHub](https://github.com/kaancelik99)

## 📜 License
MIT License
