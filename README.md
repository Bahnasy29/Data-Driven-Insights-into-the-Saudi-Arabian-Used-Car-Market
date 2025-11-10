# Data-Driven Insights into the Saudi Arabian Used Car Market

## Project Objective

**"Analyzing the Saudi Used Car Market to Identify Sales Growth Opportunities"**

---

## Dataset Overview

- **Total Records:** 8,035 rows × 13 columns
- **Analysis Period:** 1963 - 2022 (vehicle years)
- **Total Manufacturers:** 54 unique brands

---

## Executive Summary

### Market Size & Value
- **Total Market Value:** 431 Million SAR
- **Luxury Car Segment:** 1,147 vehicles
- **Negotiable Listings:** 2,527 vehicles (31.45% of inventory)

### Market Leaders
- **Top Make:** Toyota
- **Top Model:** Land Cruiser
- **Top Configuration:** Full Options
- **Top Fuel Type:** Gas
- **Top Transmission:** Automatic
- **Top Region:** Riyadh

### Premium Segment
**Highest-Priced Brands:** Ferrari, Rolls-Royce, Aston Martin

**Luxury Brands in Dataset (15 manufacturers):**
Mercedes, BMW, Lexus, Cadillac, INFINITI, Audi, Porsche, Land Rover, Jaguar, Rolls-Royce, Bentley, Aston Martin, Maserati, Ferrari, Genesis

---

## Key Market Insights

### Pricing Dynamics

#### Transmission Type Impact
- **Automatic vehicles** command higher prices than manual transmissions
- Reflects market preference for convenience and modern features

#### Age-Based Pricing Trends
- **Post-2000 vehicles** generate significantly higher revenue than older models
- **Post-2010 vehicles** show the highest price points in the market
- Clear premium for newer inventory

#### Mileage Correlation
- **Lower mileage vehicles** consistently price higher
- High-mileage vehicles show significant price depreciation
- Pre-2000 vehicles typically have higher mileage and manual transmissions

### Geographic Distribution

**Top 3 Markets by Sales Value:**
1. Riyadh (Primary market)
2. Jeddah (Secondary market)
3. Dammam (Tertiary market)

These three cities account for the majority of high-value used car transactions.

### Segment Performance

#### Volume Leaders
- **Toyota:** Dominates in both sales volume and negotiable listings
- Highest occurrence in dataset reflecting market saturation and demand

#### Value Leaders
- **Mercedes:** Leads in outlier pricing (premium segment)
- **Luxury Segment:** Generates 143M SAR out of 431M total (33% of market value)
- 15 luxury manufacturers (25% of brands) drive one-third of total revenue

#### Price Outlier Analysis
- Premium segment outliers contribute **105 Million SAR** in sales
- **Mercedes** leads in high-value outlier transactions
- Significant price increase observed for vehicles manufactured after 2010

### Negotiable Listings Analysis

**Critical Finding:** All listings with price = 0 have Negotiable = True

**Interpretation:** 
- These vehicles represent unsold inventory or pending negotiations
- Price marked as 0 indicates finalization pending buyer negotiation
- 2,527 negotiable cars (31.45%) represent significant untapped revenue potential

---

## Data Engineering

### Newly Created Features

1. **Car_Age:** Calculated age of vehicle from manufacture year
2. **Is_Luxury:** Binary classification for luxury brand identification
3. **Average_Price_Per_Options:** Pivot analysis of pricing by feature packages
4. **Count_Type_Per_Make:** Pivot table showing model distribution per manufacturer
5. **Price_Per_Make:** Manufacturer-level pricing aggregation
6. **Negotiable_Cars_Pivot:** Analysis table for negotiable inventory

### Data Quality Notes
- **Outliers:** Flagged for analysis but retained in dataset for market insights
- Outliers provide valuable information about premium segment behavior

---

## Strategic Recommendations

### 1. Inventory Focus Strategy
**Priority:** Post-2010 automatic vehicles with low mileage and full options

**Rationale:** This segment demonstrates highest price points and fastest sales velocity. Market strongly prefers:
- Automatic transmission
- Gas fuel type
- Low mileage
- Recent model years (especially 2010+)
- Full option packages

### 2. Brand Portfolio Optimization
**High Priority Brands:** Toyota and Mercedes

**Action Items:**
- Expand Toyota inventory (volume leader)
- Increase Mercedes allocation (value leader)
- Focus on identified top 10 performing models
- Leverage brand-specific marketing strategies

### 3. Luxury Segment Expansion
**Opportunity Size:** 143M SAR from just 15 manufacturers

**Recommendations:**
- Develop specialized luxury division
- Enhanced marketing for premium segment
- White-glove service for high-value transactions
- Focus on post-2010 luxury inventory

### 4. Geographic Market Prioritization
**Tier 1 Markets:** Riyadh, Jeddah, Dammam

**Action Items:**
- Allocate marketing budgets proportional to market size
- Establish premium showrooms in these cities
- Develop region-specific inventory strategies
- Consider market-specific pricing strategies

### 5. Negotiable Inventory Management
**Critical Issue:** 2,527 vehicles (31.45%) in negotiable status

**Immediate Actions Required:**
- Implement aggressive pricing strategy for negotiable inventory
- Launch promotional campaigns targeting unsold units
- Establish clear pricing guidelines to reduce negotiation time
- Consider time-based discounts to accelerate turnover
- Improve price discovery mechanisms

### 6. Age-Based Acquisition Strategy
**Focus:** Vehicles manufactured after 2000, preferably 2010+

**Implementation:**
- Adjust acquisition criteria to prioritize newer inventory
- Consider premium pricing for post-2010 vehicles
- Gradually phase out pre-2000 inventory except for collectibles
- Market modern features and reliability of newer vehicles

---

## Expected Impact Summary

> "Identified key factors driving used car sales in Saudi Arabia — recommending focus on post-2010 automatic cars and luxury brands in Riyadh and Jeddah to increase revenue by targeting high-value segments."

### Projected Outcomes
- Reduced negotiable inventory from 31.45% through targeted promotions
- Increased average transaction value through luxury segment focus
- Improved inventory turnover in top 3 geographic markets
- Enhanced margin capture on premium (post-2010) vehicles

---

## Next Steps

1. **Immediate (0-30 days)**
   - Address negotiable inventory backlog
   - Launch targeted campaigns in Riyadh, Jeddah, Dammam
   
2. **Short-term (1-3 months)**
   - Adjust acquisition strategy toward post-2010 vehicles
   - Expand luxury brand inventory
   
3. **Medium-term (3-6 months)**
   - Develop luxury division with specialized services
   - Implement geographic expansion in tier 1 markets
   
4. **Long-term (6-12 months)**
   - Build brand partnerships with Toyota and Mercedes
   - Establish market leadership in premium segment

---

## Methodology & Tools

- **Data Analysis:** Python/Pandas
- **Visualization:** Data visualization libraries
- **Feature Engineering:** Custom calculations and pivot tables
- **Statistical Analysis:** Outlier detection and correlation analysis

---

## Contributing

For questions about this analysis or to contribute additional insights, please open an issue or submit a pull request.

---

*Analysis based on 8,035 used car transactions in Saudi Arabia (1963-2022)*
