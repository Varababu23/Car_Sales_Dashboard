Car Sales Analysis Dashboard – Insights from CarDekho Data


This Power BI dashboard offers an interactive exploration of car sales data sourced from CarDekho’s Kaggle dataset, illuminating key pricing trends, vehicle types, and buying preferences within India’s automotive market.

Source

Kaggle Dataset: “Vehicle Dataset from CarDekho” (https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)

Data Columns Brief Description

Car_Name: Name/model of the car (e.g., Maruti Swift)

Year: Year of car registration or manufacture

Selling_Price: Resale price/value of the car (in lakhs INR)

Present_Price: Ex-showroom price when the car was new (in lakhs INR)

Kms_Driven (Driven_kms): Total kilometers driven

Fuel_Type: Type of fuel (Petrol, Diesel, CNG, etc.)

Seller_Type: Type of seller (Dealer/Individual)

Transmission: Manual or Automatic

Owner: Ownership status (First, Second, etc.)

Mileage: Fuel efficiency (km/l or km/kg)

Engine: Engine capacity (in cc)

Max_Power: Maximum power output (in bhp)

Seats: Number of seats

Color: Color of the vehicle (if included in your version)

(You may tailor the column list to match your data extract.)

Tools & Technologies


Power BI (dashboarding, data modeling)

DAX (custom metrics, calculations)

SQL/Excel (data preparation)

CarDekho Kaggle Dataset

Key Features & Visualizations


1. Brand Filters
What it does:
Allows users to focus their analysis on selected car manufacturers, making comparative evaluation of trends (e.g., Maruti vs. Hyundai) easy and interactive.

Insights:
Quickly compare market performance, pricing, and mileage across brands of your choice.

2. Sum of Mileage by Year
What it does:
Aggregates the total mileage reported by all cars sold each year.

Insights:
Helps identify periods of higher vehicle usage/sales activity and hint at changing consumer driving patterns or the market’s shift towards higher or lower-mileage vehicles.

3. Sum of Price by Year
What it does:
Displays the total value of used cars sold annually.

Insights:
Shows growth or contraction in the car resale market over time—spikes or dips may indicate broader economic trends or consumer behavior changes.

4. Sum of Price by Year and Brand
What it does:
Breaks down total annual sales value by each car brand.

Insights:
Highlights which brands dominated the resale market in specific years and uncovers brand popularity cycles or market share changes.

5. Sum of Mileage by Brand and Condition
What it does:
Compares the mileage performance of cars by brand, segmented by condition (New vs. Used).

Insights:
Reveals brand-wise reliability perceptions, how used vs. new mileage varies, and whether certain brands retain value and low mileage better than others.

6. Count of Model by Color



What it does:
Visualizes the popularity of different car colors among models sold.

Insights:
Identifies color trends by model—helpful for dealerships, marketing teams, or manufacturers to optimize offerings and promotions.

How to View & Use


Download the .pbix file from this repository.

Open with Power BI Desktop (version 2.104.xxx or later recommended).

Use interactive slicers and filters to explore the data by brand, year, vehicle condition, and more.

Business Value



This dashboard empowers automotive businesses, dealers, and analysts to:

Uncover brand-specific and market-wide sales/value trends

Track shifts in buyer preferences by color, model, or fuel type

Compare annual performance and strategize inventory management

Inform targeted marketing and pricing strategies backed by evidence
