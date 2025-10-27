# One-Day-Hotel-Revenue-Booking-Insights-Dashboard-using-Power-BI

🧭 **Project Overview**

This project analyses hotel booking data across five major cities for a single check-in date (03 August 2016). The dashboard and report provide insights into booking performance, guest ratings, revenue trends, and room type popularity. All steps from initial data inspection, cleaning, transformation, through to interactive dashboard creation, are meticulously documented.
________________________________________

📂 **Dataset Description**

The dataset contains 100 records with the following fields:
-	HotelID: Unique hotel identifier
-	HotelName, Location: Brand & city
-	RoomType: Deluxe, Suite, Double, Single
-	Rating: Guest/system rating (1–5)
-	PricePerNight: Room price in USD
-	BookingStatus: Confirmed, Cancelled, Pending, Not Defined
-	CheckInDate: Date of booking (all 03 August 2016)
________________________________________

🎯 **Problem Statement & Objectives**

The objective is to help hotel management:
-	Identify revenue drivers by city, hotel, and room type
-	Understand booking status patterns (cancellations, pending, confirmation rates)
-	Reveal actionable guest preferences
-	Visualize the business snapshot for an operational day
________________________________________

🧼 **Data Cleaning Process**

1.	Duplicates: Checked and removed any duplicate bookings.
2.	Missing Data: Examined all columns, flagged ‘Not Defined’ statuses for review.
3.	Formatting: Standardized text fields (capitalization, whitespace).
4.	Range & Consistency: Validated Rating and PricePerNight for outliers and logical ranges.
5.	Uniform Dates: Ensured single-check-in date consistency.
________________________________________

🔧 **Data Transformation & Feature Engineering**

-	Aggregated booking and price statistics by RoomType, Location, and HotelName.
-	Derived key metrics: total guests, revenue, mean price, and ratings.
-	Pivoted data for dashboard visuals (e.g., RoomType by Location, BookingStatus by Count).
-	Encoded categorical states for visualization (pie/bar charts, trend graphs).
________________________________________

📈 **Key Insights & Dashboard Interpretation**

- Deluxe rooms had the highest bookings (40%). Miami and New York generated the most revenue.
-	Confirmed bookings: 39%—potential to improve with better process automation and communication.
-	Mountain Inn had the highest revenue and total guest ratings; Ocean View lagged behind.
-	Clear opportunities exist to increase sales by optimizing inventory and targeting cancellations.
________________________________________

✅ **Business Recommendations**

-	Increase availability of Deluxe/Suite rooms in top-performing cities.
-	Investigate reasons for cancellations and pending status.
-	Monitor and enhance guest experience in underperforming hotels.
-	Automate booking status tracking to reduce ‘Not Defined’ cases.
________________________________________

🛠️ **Tools and Technologies** 

-	📊 Power BI: Dashboard creation and visualization. 
-	🧠 DAX / M Language: Calculated columns, measures, logic modelling. 
