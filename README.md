# ✈️ MakeMyTrip Travel & Hospitality Analytics Dashboard

An interactive **Power BI** dashboard that analyzes MakeMyTrip booking data from **Jan 2024 to Aug 2026**. It turns raw booking, customer, and revenue data into insights on demand, revenue drivers, booking channels, and cancellations.

![Dashboard Preview](images/makemytrip_dashboard.png)

## 📌 Project Overview

Travel platforms handle thousands of bookings across flights, hotels, buses, trains, and holiday packages. This project answers the questions a business team would ask:

- Which destinations and services drive the most bookings and revenue?
- How do bookings and revenue change from month to month?
- Which channels and customer segments contribute the most?
- How many bookings are completed, confirmed, or cancelled?

## 📊 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Bookings | 8K |
| Total Revenue | 160.84M |
| Total Customers | 4K |
| Avg Booking Value | 20.11K |
| Cancellation Rate | 12.4% |
| Discount % | 11.11 |
| Customer Rating | 3.89 / 5 |

## 🔍 Dashboard Sections

- **Top 10 Travel Destinations:** Guwahati leads with 322 bookings, followed by Bengaluru (303) and Indore (302).
- **Booking & Revenue Trend:** Monthly combo chart comparing total bookings against total revenue.
- **Booking Mix by Service:** Flight (32.01%), Hotel (28.49%), Bus (14.89%), Holiday Package (14.43%), Train (10.19%).
- **Booking Channel Analysis:** Android App (41.98%), iOS App (22.99%), Mobile Web (20.21%), Desktop (14.83%).
- **Bookings by Customer Segment:** Regular (3.2K), New (2.8K), MMT Black (1.2K), Corporate (0.8K).
- **Booking Status Overview:** Completed (5.0K), Confirmed (2.0K), Cancelled (1.0K).
- **Revenue by Service Type:** Holiday Package (70M) and Hotel (65M) lead, ahead of Flight (23M), Bus (2M), and Train (1M).
- **Interactive Slicers:** Filter by Year, Month, Airline, Gender, Service, Destination, State, and Hotel.

## 💡 Key Insights

- **Holiday Packages** are the top revenue service, contributing the most revenue despite a smaller share of bookings than flights.
- **Flights** account for the largest share of bookings (32%) but contribute far less revenue than packages and hotels.
- **Android App** is the dominant booking channel at nearly 42%, so mobile is the key platform.
- **Regular and New customers** make up most bookings, so acquisition and repeat business both matter.
- About **1 in 8 bookings is cancelled**, which points to a chance to improve retention and refund policies.
- Bookings are spread fairly evenly across the top 10 destinations, with Guwahati slightly ahead.

## 🛠️ Tools & Technologies

- **Power BI Desktop:** dashboard design and visualization
- **DAX:** KPI and measure calculations
- **Power Query:** data cleaning and transformation
- **Data Modeling:** relationships between bookings, customers, and destinations

## 📁 Repository Structure
├── MakeMyTrip_Dashboard_Dataset.xlsx
├── makemytrip.pbix
├── Screenshot 2026-09-14 205912.png
└── README.md
