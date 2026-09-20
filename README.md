# Uber Rides & Revenue Analysis — Power BI Dashboard
 
An interactive Power BI dashboard analyzing Uber ride bookings, revenue, and service quality across vehicle types (Auto, Bike, Go Mini, Go Sedan, Premier, Uber XL).
 
## Dashboard Preview
 
The dashboard includes:
- **KPI Cards**: Completed Bookings (93K), Lost Bookings (57K), Revenue (52M), Total Distance (2.51M), Avg. Distance (24.64)
- **Completed Bookings Trend**: Monthly line chart of completed rides (Jan–Dec)
- **Revenue Trend**: Monthly bar chart of revenue (Jan–Dec)
- **Revenue by Vehicle Type**: Horizontal bar chart comparing Auto, Bike, Go Mini, Go Sedan, Premier Sedan, and Uber XL
- **Ride Status Breakdown**: Donut gauges for Completed, Cancelled, and Incomplete rides
- **Top Locations**: Top pickup point (Khandsa) and top drop point (Ashram)
- **Ratings**: Average Customer Rating (4.40) and Average Driver Rating (4.23)
- **Vehicle Type Filter**: Icon-based slicer to filter the report by vehicle category
## Objective
 
To analyze ride booking patterns, revenue performance, and service quality for an Uber-style ride-hailing business, helping stakeholders identify:
- Which vehicle types generate the most revenue
- Seasonal/monthly trends in bookings and revenue
- Ride completion vs. cancellation vs. incomplete ride rates
- Top pickup and drop-off hotspots
- Customer and driver satisfaction levels
## Tools Used
 
| Tool | Purpose |
|---|---|
| Power BI | Dashboard design, DAX measures, interactive visuals |
| Power Query | Data cleaning and transformation |
| Excel / CSV | Source data |
 
## Dataset
 
Ride-level booking data including fields such as:
- Booking ID, Date, Vehicle Type
- Booking Status (Completed / Cancelled / Incomplete)
- Fare / Revenue, Distance
- Pickup Location, Drop Location
- Customer Rating, Driver Rating
## Key Metrics (DAX Measures)
 
- `Completed Bookings` — count of rides with status = Completed
- `Lost Bookings` — count of Cancelled + Incomplete rides
- `Total Revenue` — sum of fare across completed rides
- `Total Distance` / `Avg Distance` — trip distance aggregates
- `Avg Customer Rating` / `Avg Driver Rating`
- `Revenue by Vehicle Type` — revenue split across ride categories
## Key Insights
 
- Auto leads revenue generation (₹13M), followed closely by Bike (₹11M) and Go Mini (₹10M)
- Uber XL contributes the least revenue (₹2M), suggesting lower demand or fleet availability for premium rides
- ~38% of total bookings (57K of 150K) were lost to cancellations or incomplete trips — a significant drop-off worth investigating
- Khandsa and Ashram emerge as the top pickup and drop hotspots, useful for driver allocation and surge planning
- Customer ratings (4.40) are consistently higher than driver ratings (4.23), pointing to potential driver-side service gaps
## How to Use
 
1. Open `Uber_Dashboard.pbix` in Power BI Desktop
2. Use the vehicle-type icon slicer at the bottom to filter by ride category
3. Toggle between **Month** and **Quarter** views on the trend charts
4. Hover over visuals for tooltips with exact values
## Files in This Repository
 
```
├── Uber_Dashboard.pbix        # Power BI dashboard file
├── uber_dashboard.png         # Dashboard screenshot/preview
└── README.md                  # Project documentation
```
 
## Author
 
**Chetan**
Data Analyst | Business Analyst
Delhi NCR, India
 
