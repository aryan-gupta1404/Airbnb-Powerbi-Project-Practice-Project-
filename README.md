# Airbnb-Powerbi-Practice-Project-
An interactive Power BI dashboard designed to explore Airbnb listings, reviews, ratings, pricing, review frequency, seasonality, and host trust signals across 10 major cities.

This project was recreated as a hands-on Power BI learning project based on Mansi Goel's Airbnb Power BI project, with a focus on understanding the complete workflow from data preparation and modeling to DAX calculations and interactive dashboard design.

# 1. Project Overview

The Global Airbnb Performance Dashboard provides an analytical view of Airbnb's performance across different cities, property types, review patterns, ratings, and host characteristics.

The dashboard is divided into three major analytical areas:

Introduction & Growth — Overview of listings, cities, hosts, property types, reviews, and listing growth over time.
Ratings & Market Share — Comparison of listings, reviews, pricing, Superhost status, and detailed ratings across cities.
Reviews & Seasonality — Analysis of reviewer frequency, monthly review patterns, and host identity and trust signals.

This project provided hands-on experience with the complete Power BI workflow rather than focusing only on individual features.

# 2. Short Description / Purpose

The purpose of this dashboard is to provide an interactive way to analyze Airbnb performance across major cities and identify patterns in listings, reviews, ratings, pricing, and seasonality.

The dashboard can be used to explore questions such as:

Which cities have the largest share of Airbnb listings and reviews?
How do average prices differ by property type?
How frequently do customers leave reviews?
How do ratings differ across cities?
How does review activity change throughout the year?
What proportion of hosts provide identity or trust signals?

# 3. Tech Stack

The dashboard was built using the following tools and technologies:

Power BI Desktop — Main platform for data modeling, analysis, visualization, and dashboard development.
Power Query — Used for data preparation and transformation.
DAX (Data Analysis Expressions) — Used to create calculated columns and measures.
Data Modeling — Relationships between the Listings and Reviews tables were used for analysis and cross-filtering.
File Formats — .pbix / .pbit for Power BI development and .png for dashboard previews.

# 4. Data Source

The project uses Airbnb listing and review data covering 10 major cities.

The dataset contains information related to:

Airbnb listings
Cities
Hosts
Property types
Reviews
Reviewer IDs
Listing prices
Ratings
Superhost status
Host identity verification
Review dates

The completed dashboard reports approximately:

279K listings
10 cities
182K hosts
144 property types
5.37M reviews

# 5. Features and Highlights
**5.1 Business Problem**

Airbnb generates large amounts of data across listings, reviews, prices, ratings, and host characteristics. Looking at the raw data makes it difficult to quickly compare cities, understand customer review behavior, or identify seasonal patterns.

This dashboard provides an interactive way to explore these patterns and turn the underlying data into more accessible insights.

**5.2 Goal of the Dashboard**

The main goals of the dashboard are to:

Explore Airbnb performance across different cities.
Compare listings and reviews across markets.
Analyze pricing and property types.
Understand customer review frequency.
Examine ratings across different dimensions.
Identify seasonal patterns in review activity.
Analyze host trust and identity signals.
Present the analysis through an interactive Power BI report.

**5.3 Dashboard Walkthrough**
Page 1 — Introduction & Growth

The first page provides a high-level overview of the Airbnb dataset.

Key KPIs include:

Total Listings
Cities
Hosts
Property Types
Reviews

The New Listings analysis shows Airbnb listing growth from approximately 2008 to 2020, with segmentation by:

Entire Place
Hotel Room
Private Room
Shared Room

The page also highlights different stages of Airbnb's growth and the impact of COVID-19 on listing activity.

Page 2 — Ratings & Market Share

The second page focuses on differences between Airbnb markets.

Key analyses include:

Market Share by City
Average Price by Property Type
Superhost vs. Non-Superhost analysis
Detailed city-level ratings

The ratings analysis compares:

Accuracy
Cleanliness
Communication
Location
Value

The dashboard highlights Mexico City and Rio de Janeiro among the highest-rated cities overall, while cleanliness and value are identified as relatively weaker rating dimensions in the analysis.

Page 3 — Reviews & Seasonality

The third page focuses on customer review behavior and seasonal patterns.

Review Frequency

The dashboard analyzes how frequently customers leave reviews.

Key observations include:

Most customers leave a review only once.
Approximately 98.8% of customers leave reviews three times or fewer.
One customer is associated with 283 reviews, which is highlighted as a potential data-quality anomaly or unusually active traveler.
Cumulative Review Analysis

The review-frequency analysis uses DAX calculations to determine cumulative reviewer percentages across different review frequencies.

This section provided practical experience with:

Calculated columns
Measures
DISTINCTCOUNT
CALCULATE
FILTER
ALL
Filter context
Cumulative calculations
Seasonality

Monthly review activity is compared across:

Mexico City
New York
Paris
Rome
Sydney

The dashboard highlights stronger review activity for Paris and Rome during the European summer months and increased activity in New York during November and December.

Host Trust & Identity

The dashboard also analyzes:

Profile picture availability
Identity verification

The analysis shows that more than two-thirds of Airbnb hosts are fully verified, while most hosts provide at least one trust signal.

# 6. Key Learning Outcomes

This project provided hands-on experience with several Power BI concepts.

Power BI
Building multi-page dashboards
Interactive report design
Slicers and filtering
Dashboard navigation
Bookmarks
Data visualization
Data Preparation
Data transformation using Power Query
Preparing fields for analysis
Working with dates and months
Creating analysis-ready columns
Data Modeling
Understanding relationships between tables
Using relationships for cross-filtering
Understanding how model structure affects DAX calculations
DAX

I worked with both calculated columns and measures, including:

COUNT
DISTINCTCOUNT
CALCULATE
FILTER
ALL
DIVIDE
Variables
Cumulative calculations

One of the biggest lessons from the project was understanding the difference between calculated columns and measures, particularly while working on the review-frequency analysis.

# 7. Challenges and Takeaways

The most challenging part of the project was DAX.

Initially, I was following the project step-by-step and reproducing the formulas shown in the tutorial. When some calculations did not produce the expected results, I had to investigate the underlying logic.

This helped me understand that simply copying DAX formulas is not enough.

I need to understand:

What am I trying to calculate, what context is the calculation operating in, and why should this be a measure or a calculated column?

The debugging process was frustrating at times, but it made the concepts much more memorable and showed me the areas where I need more practice.

# 8. Favorite Feature

One of my favorite Power BI features from this project was Bookmarks.

I enjoyed using bookmarks to create a more interactive dashboard experience, and I plan to incorporate them into my upcoming Power BI projects.

# 9. Dashboard Preview
Page 1 — Introduction & Growth




Page 2 — Ratings & Market Share




Page 3 — Reviews & Seasonality




Replace the image paths above with the actual screenshots uploaded to the repository.

# 10. Future Improvements

As this was a guided learning project, my next focus is to build on what I learned by:

Practicing DAX more extensively.
Strengthening my understanding of filter context.
Improving data modeling skills.
Building more dashboards with less guidance.
Applying Power BI concepts to different datasets.
Gradually moving toward completely independent projects.
# 11. Acknowledgement

This project was recreated as a learning exercise based on Mansi Goel's Airbnb Power BI project.

Credit to Mansi Goel for creating and sharing the original project and walkthrough.

The purpose of this recreation was to learn and practice Power BI, DAX, data modeling, and dashboard development.
