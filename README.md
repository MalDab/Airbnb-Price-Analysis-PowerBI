# Airbnb-Price-Analysis-PowerBI
Interactive Power BI dashboard analyzing Airbnb pricing trends in Barcelona, Berlin, and Budapest. Identifying price drivers, location impact, and host performance across three major European cities. Features ETL (Power Query), DAX, and Star Schema data modeling.

<img width="1416" height="793" alt="Airbnb_Price_Analysis_Dąbek_Małgorzata_1" src="https://github.com/user-attachments/assets/4fb66a23-6f4c-4c44-8e09-7ff18e4deeeb" />
<img width="1422" height="786" alt="Airbnb_Price_Analysis_Dąbek_Małgorzata_2" src="https://github.com/user-attachments/assets/41427188-c295-4dfd-8fb8-12fcb498bf07" />

## Project Overview
This project provides a comprehensive analysis of Airbnb rental prices in three major European cities: Barcelona, Berlin, and Budapest. The goal was to identify key factors influencing accommodation costs, such as property type, location, and host status. The project was created in Polish.

## Key Business Questions
* The analysis aims to answer the following questions:
* Which of the analyzed cities is the most expensive? 
* How do prices fluctuate between weekdays and weekends? 
* What is the impact of "Superhost" status and guest ratings on price? 
* Does proximity to the city center justify higher rates?

## Data Source & Methodology
* Source: The dataset "Airbnb Prices in European Cities" was sourced from Kaggle.
* Tools Used: Power BI, Power Query (ETL), DAX.
* Data Transformation: Data cleaning involved handling missing values, changing data types, and translating attributes.
* Data Model: A Star Schema was implemented, consisting of a central Fact Table (Fact_obiekt) and several Dimension Tables (City, Location, Property Type, Date Type, and Ratings).

## Key Insights
* Price Leader: Barcelona is the most expensive city with an average price of €313.13, while Budapest is the most affordable at €211.04.

  <img width="617" height="317" alt="Airbnb_Price_Analysis_Dąbek_Małgorzata_3" src="https://github.com/user-attachments/assets/9fd1b51e-e7a5-4ebc-9544-fc97b4e12af3" />
   
* Weekend Surge: In general, prices are higher during weekends due to increased tourist demand.
  
  <img width="656" height="212" alt="Airbnb_Price_Analysis_Dąbek_Małgorzata_4" src="https://github.com/user-attachments/assets/e2c18197-c469-4f6f-b1bc-12729a60724e" />
  
* Business vs. Leisure: Interestingly, in Barcelona and Berlin, renting an entire home/apartment is more expensive on weekdays, likely due to a high volume of business travel and conferences.

  <img width="653" height="357" alt="Airbnb_Price_Analysis_Dąbek_Małgorzata_5" src="https://github.com/user-attachments/assets/c629ab37-bfee-469e-9a22-7886c7a4eb74" />
  
* Extreme Values: The most expensive listing was found in Barcelona (€6,950.64 per night), while the cheapest was in Budapest (€38.99).
   <img width="601" height="145" alt="Airbnb_Price_Analysis_Dąbek_Małgorzata_6" src="https://github.com/user-attachments/assets/465d08ce-d481-4bc8-a4b7-cedd4883e6c3" />

* Quality-Price Correlation and the "Superhost" Premium: Listings with higher guest ratings and cleanliness scores command significantly higher prices. Holding a Superhost status is directly linked to higher rental rates, indicating that a proven track record of hospitality allows hosts to apply premium pricing.

  <img width="673" height="262" alt="image" src="https://github.com/user-attachments/assets/2808d87c-3431-4df1-a53e-7cc7f3d36e40" />

## How to View the Project
1. Static Report: You can find the full analysis and visualizations in the attached [Download Full Report (PDF)](Airbnb_Price_Analysis_Dąbek_Małgorzata.pdf) file
2. Raw Data: The original .pbix file is available in the repository for technical review: [Download Power BI File (PBIX)](Airbnb_Price_Analysis_Dąbek_Małgorzata.pbix)
