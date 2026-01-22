# Airbnb Occupancy Analysis – Paris

## Project Overview
This project analyzes how **location, pricing, room type, competition, and proximity to tourist attractions** influence Airbnb **occupancy rates in Paris, France**. Using data-driven statistical and machine learning techniques, the study identifies high-performing neighborhoods, optimal room types, and actionable pricing strategies for hosts and investors.

The analysis was conducted as part of the **BIA 672 – Big Data Decision Tools** course.

---

## Research Objectives
- Identify **Paris neighborhoods** with the highest and lowest Airbnb occupancy rates
- Analyze the impact of:
  - Room type
  - Pricing
  - Competition (number of listings per host)
  - Distance from major tourist attractions (Eiffel Tower)
- Evaluate whether oversupply reduces occupancy
- Extract insights from **guest reviews** using text mining and sentiment analysis
- Provide **data-driven recommendations** for hosts and investors

---

## Dataset Information
- **City:** Paris, France  
- **Source:** InsideAirbnb  
- **Listings:** ~91,000  
- **Key Features:**
  - Occupancy rate (adjusted)
  - Price (log-transformed)
  - Room type
  - Neighborhood
  - Reviews & review frequency
  - Distance to Eiffel Tower
  - Host listing count
  - Availability (365 days)

---

## Methods & Techniques Used

### Exploratory & Statistical Analysis
- Neighborhood-level occupancy comparison
- Heatmaps of occupancy concentration
- One-way & Two-way ANOVA
- Tukey HSD post-hoc testing
- Kruskal-Wallis non-parametric test

### Regression & Modeling
- Linear regression
- Beta regression (occupancy as bounded variable)
- Negative binomial regression (reviews/bookings)
- Correlation analysis

### Advanced Analytics
- Principal Component Analysis (PCA)
- Clustering (pricing & occupancy segments)
- Price elasticity analysis
- Distance-based spatial modeling

### Text Mining & NLP
- Topic modeling on listing descriptions
- Sentiment analysis of guest reviews

---

## Key Findings

### Neighborhood Effects
- **Highest occupancy:** Élysée, Bourse, Opéra, Louvre  
- **Lowest occupancy:** Ménilmontant, Buttes-Chaumont, outer districts  
- Neighborhood significantly affects occupancy (p < 2e-16)

### Room Types
- **Private rooms:** Most consistent performer
- **Entire homes:** High occupancy in tourist-heavy areas
- **Shared rooms:** Surprisingly strong in business districts
- **Hotel rooms:** Lowest occupancy overall

### Pricing Impact
- Strong **negative relationship** between price and occupancy
- Higher prices → significantly lower booking rates
- Price elasticity varies by neighborhood

### Distance to Attractions
- Listings **closer to the Eiffel Tower** receive more bookings
- Distance effect is statistically significant but moderate

### Competition
- Hosts with **multiple listings** tend to have lower per-listing occupancy
- Single-listing hosts outperform in median occupancy

### Reviews & Sentiment
- Review frequency impacts bookings more than review score
- Positive sentiment correlates with higher prices and demand

---

## Business Recommendations
- Promote **private and shared rooms** over hotel-style listings
- Expand supply in **high-demand, low-supply neighborhoods** (Élysée, Opéra)
- Optimize pricing in underpriced high-occupancy clusters
- Focus marketing within **3 km of major attractions**
- Encourage hosts to improve review frequency and responsiveness

---

## Tools & Technologies
- **R / Python**
- Statistical modeling & regression
- Data visualization
- NLP & sentiment analysis
- PCA & clustering techniques

---

## 📂 Repository Structure (Suggested)
