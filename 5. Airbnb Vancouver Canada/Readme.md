# Airbnb Market (Vancouver, Canada)

This project is a comprehensive Power BI dashboard focused on the Airbnb market in Vancouver, Canada, designed to analyze (pricing, demand, occupancy, revenue efficiency, and guest experience).

The goal of this project is to simulate a real-world short-term rental performance analysis, combining advanced data modeling, DAX measures, Python-based data preparation, and interactive storytelling visuals.

This analysis covers:
- Listing performance and booking demand
- Pricing strategy and price segmentation
- Occupancy and revenue efficiency
- Review quality, superhost performance, and guest experience
- Neighborhood-level insights across Vancouver

 Report Pages:

### 1️⃣ Occupancy & Demand
- Booking Count, Booking Growth %, and Occupancy Rate
- Booking trends by month and seasonality
- Property type distribution (Entire home, Private room, Condo, etc.)
- Geographic analysis using neighborhood-level maps
- Top neighborhoods by bookings and revenue

---

### 2️⃣ Guest Experience & Reviews
- Average Review Score and Response Rate
- Superhost vs Non-Superhost performance
- Review quality by response time
- Correlation between responsiveness and review ratings
- Scatter and radar visuals for qualitative performance comparison

---

### 3️⃣ Revenue Performance
- Actual Revenue vs Estimated & Potential Revenue
- Revenue Capture Rate & Revenue Efficiency %
- Revenue contribution by price segment (Luxury, Standard, Economy, Budget)
- Booking vs Price analysis to support pricing strategy decisions
- Violin and bubble charts to analyze price dispersion and demand elasticity

## Analytical Techniques Used

- **Advanced DAX Measures**
- **Heavy Tooltip Usage**
- **Dynamic Drill-Down & Slicers**
  - Year, Quarter, and Time slicing
  - Property type, neighborhood, and host-type filtering
  - Consistent filtering behavior across pages
- **Python & Data Preparation**
  - The Airbnb dataset was **loaded and transformed using Python (Pandas)** before modeling in Power BI.
steps:
- Reading raw CSV data using Pandas
- Parsing semi-structured fields (amenities) using `ast.literal_eval`
- Creating binary indicator columns for amenities (wifi, kitchen, parking, etc.)
- Cleaning and standardizing text-based fields
- Preparing the dataset for efficient analytical modeling

- **Geographic Analysis**
---

## Dashboard Preview
<p align="center">
  <img src="./Images/Occupancy_Demand.jpg" width="90%" />
</p>

<p align="center">
  <img src="./Images/Guest_Experience_Review.jpg" width="90%" />
</p>

<p align="center">
  <img src="./Images/Revenue_Performance.jpg" width="90%" />
</p>

