# Compare Discount, Rating, and Price of Hotels in Indonesia's Big Cities December 2021

This project was created to make a dashboard to compare the average discount, rating, and price of hotels in some of the big cities in Indonesia. The dataset for this project is scraped using Beautifulsoup from the website pegipegi.com, on 08-12-2021. The cities are Jakarta, Bali, Padang, Batam, Jogja, Bandung, and Malang. From the dashboard, we can see which cities have a higher or lower average price, rating, and discount hotel for consideration to take a vacation or staycation.

I do not use any data in this project for any commercial purposes, just for learning.

Check out the Tableau Dashboard: [https://public.tableau.com/app/profile/m.hazim.mu.aafii/viz/DashboardHotelIndonesia/DashboardComparisonHotel?publish=yes](https://public.tableau.com/views/DashboardHotelIndonesia_17087592970710/DashboardComparisonHotel?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

![alt text](https://github.com/hazim17/Hotel-in-Indoensia/blob/main/data_file/Dashboard_Comparison_hotel.png?raw=true)


# This Repository Organization
```
.
├── data_file/                            : contains datasets that used in this project
  |_Dashboard_Comparison_hotel.png        : Image of the Dashboard
  |_hotel_data_full.csv                   : CSV file that is still raw
  |_hotel_data_full_clean.csv             : CSV file after cleaning without city column
  |_hotel_data_full_clean_2.csv           : CSV file after cleaning with city column
|── 1. Data gathering.ipynb               : The code to get the data using Beautifulsoup
|── 2. Data cleansing.ipynb               : The code to clean the data
└── README.md                             : Overview of this project
```
