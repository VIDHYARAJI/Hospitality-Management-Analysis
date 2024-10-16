# Hospitality Management Analysis

Introduction :

In the dynamic world of luxury hotels, AtliQ Grands encountered revenue challenges that endangered its market share. As an aspiring Data Analyst, I took on the challenge to improve the fortunes of this prestigious 5-star hotel chain in India.

Noteworthy Facts About AtliQ Grands :

➡️ AtliQ Grands stands as a five-star hotel chain with a presence in four major cities.

➡️ Across these urban centers, AtliQ Grands operates a network of seven unique properties, each strategically located to cater to diverse clientele.

➡️ These upscale properties offer guests a choice of four room categories: Elite, Premium, Presidential, and Standard, ensuring a tailored experience for every visitor.

➡️ To enhance guest convenience, AtliQ Grands offers reservations through six major booking platforms, optimizing accessibility and ease of booking.

🚀 Project Scope :

My mission was to leverage several datasets to extract valuable insights that would lead to informed decision-making at AtliQ Grands.

fact_booking: Contains data on booking ID, booking date, number of guests, room details, ratings given, revenue generated, and revenue realized. This table is pivotal for decision-making processes.

fact_aggregated_bookings: Holds data on property ID, check-in dates, room categories, successful bookings, and capacity, crucial for key booking and occupancy metrics.

dim_date: Contains date-related info, including dates, week numbers, and day types (weekend/weekday) for analyzing booking trends over time.

dim_hotels: Details properties (property ID, name, category, cities) essential for understanding the hotel's characteristics.

dim_rooms: Provides room IDs and classes to analyze room popularity and profitability.

🔍 Analysis Flow :

➡️ Data Analysis - Performed data exploration by examining the structure of datasets, identifying unique values, and grouping data by categories. Conducted in-depth analysis on key performance metrics such as occupancy rates, revenue generated, and revenue realized.

➡️ Data Cleaning - Ensured dataset integrity by resolving missing values and removing outliers using the 3-standard deviation formula, preparing the data for comprehensive analysis.

➡️ Data Visualization - Used Matplotlib and Plotly to create insightful visualizations that provides a better understanding.

➡️ Data Transformation: Added new columns to the fact table, enhancing decision-making processes.

➡️ Insight Generation - Generated meaningful insights by merging the fact table with dimension tables, focusing on key decision-making columns.

Tools used :

* Python (Pandas, Matplotlib, Plotly)

* Colab for coding
