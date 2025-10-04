# Maximizing Revenue for Cab Drivers

## 📊 Project Overview

This data-driven research project explores the relationship between payment methods and fare amounts in NYC taxi operations to identify strategies for maximizing driver revenue while maintaining customer satisfaction. By analyzing real-world taxi trip data, this study uncovers actionable insights into customer payment preferences and trip characteristics.

---

## 🎯 Research Question

**Is there a link between total fare and payment method?**

Can we encourage customers to use payment types that yield higher revenue for drivers without negatively affecting the customer experience?

---

## 📁 Dataset

**Source:** NYC Taxi Trip Dataset

**Key Features Analyzed:**
- `passenger_count` - Number of passengers per trip
- `payment_type` - Payment method (Card/Cash)
- `fare_amount` - Total fare charged
- `trip_distance` - Distance traveled in miles
- `duration` - Trip duration in minutes

**Dataset Size:** 3,670,831 rows × 5 columns (after cleaning)

---

## 🔍 Methodology

### 1. Data Cleaning
- Handled missing values and inconsistencies
- Removed outliers using IQR (Interquartile Range) method
- Applied outlier detection for `fare_amount`, `trip_distance`, and `duration`
- Standardized categorical variables

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics for fare amounts by payment type
- Distribution analysis of passenger counts
- Correlation analysis between trip characteristics

### 3. Feature Engineering
- Created payment type categories
- Aggregated passenger count distributions
- Calculated percentage distributions for key metrics

### 4. Data Visualization
- QQ plots for normality assessment
- Stacked bar charts for payment type vs passenger count
- Distribution plots for fare amounts

### 5. Hypothesis Testing
**Null Hypothesis (H₀):** There is no significant difference in average fare amounts between card and cash payments.

**Alternative Hypothesis (H₁):** Card payments result in significantly different average fare amounts compared to cash payments.

**Statistical Test:** Independent samples T-test (two-tailed)

---

## 📈 Key Findings

### Payment Method Insights
- **Card Dominance:** Card payments account for **67.5%** of all transactions
- **Cash Usage:** Cash payments represent **32.5%** of transactions
- **Revenue Impact:** Card payments are associated with higher average trip distances and fare amounts

### Trip Characteristics
- **Higher-Value Trips:** Customers prefer card payments for longer, more expensive trips
- **Distance Correlation:** Card payments show positive correlation with trip distance and duration
- **Revenue Opportunity:** Encouraging card usage may naturally align with higher-revenue trips

### Passenger Count Distribution
- **Single Passengers Dominate:** 
  - 40.8% of card transactions are single-passenger rides
  - 20.4% of cash transactions are single-passenger rides
- **Group Travel Trend:** Transaction frequency decreases as passenger count increases
- **Market Gap:** Larger groups may be underserved or prefer alternative transportation

### Statistical Validation
- T-test results confirm significant difference in fare amounts between payment types
- QQ plot analysis validates data distribution assumptions
- Findings are statistically robust after outlier removal

---

## 💡 Business Recommendations

### For Taxi Companies
1. **Promote Card Payment Infrastructure:** Ensure all vehicles have reliable card payment systems
2. **Incentivize Digital Payments:** Consider small discounts or loyalty points for card users
3. **Target Long-Distance Customers:** Market premium services to customers likely to take longer trips

### For Drivers
1. **Encourage Card Payments:** Higher average fares associated with card transactions
2. **Focus on Single Passengers:** Primary market segment with consistent demand
3. **Airport/Long-Distance Routes:** Prioritize routes where card payments are more common

### Strategic Insights
- Card payment preference indicates customer comfort with digital transactions
- Opportunity to develop loyalty programs tied to payment methods
- Potential to increase average fare by understanding payment-distance relationship

---

## 🛠️ Tools & Technologies

**Programming Language:** Python 3.x

**Libraries Used:**
- `pandas` - Data manipulation and analysis
- `matplotlib` - Data visualization
- `seaborn` - Statistical data visualization
- `scipy` - Statistical testing
- `statsmodels.api` - QQ plots and statistical modeling
- `numpy` - Numerical computations

**Development Environment:** Jupyter Notebook

---

## 📊 Visualizations

The project includes:
- **QQ Plots** - Normality assessment for fare amounts
- **Stacked Bar Charts** - Payment type distribution across passenger counts
- **Distribution Plots** - Fare amount distributions by payment method
- **Summary Statistics Tables** - Descriptive analysis results

---

## 🔬 Statistical Analysis

### Hypothesis Test Results
- **Test Type:** Independent samples T-test
- **Significance Level:** α = 0.05
- **Conclusion:** Significant difference found between card and cash payment fare amounts
- **Practical Implication:** Payment method is a meaningful predictor of trip revenue

---

## 📝 Data Storytelling

This analysis tells the story of modern urban transportation economics. As digital payments become the norm, we see a clear pattern: customers who choose card payments tend to take longer, more valuable trips. This isn't just about payment preference—it reveals deeper insights about customer behavior, trip planning, and revenue optimization opportunities.

The dominance of single-passenger trips suggests a personalized, on-demand service model, while the decline in multi-passenger transactions points to potential market expansion opportunities in group transportation.

For drivers, understanding these patterns means more than just accepting cards—it means positioning themselves for higher-revenue trips and making strategic decisions about when and where to operate.

---

## 🚀 Future Work

- Expand analysis to include time-based patterns (rush hour, weekends)
- Investigate geographic factors affecting payment preferences
- Develop predictive model for fare amounts based on trip characteristics
- Analyze seasonal trends in payment method usage
- Study impact of tipping on total revenue by payment type

---

## 👤 Author

**Project Type:** Data Analysis & Statistical Research  
**Domain:** Transportation & Revenue Optimization  
**Completion Date:** 2025

---

## 🙏 Acknowledgments

- NYC Taxi & Limousine Commission for providing the dataset
- Open-source Python community for excellent data science tools
- Statistical methodologies based on established research practices

---

## 📧 Contact

For questions, suggestions, or collaboration opportunities, please feel free to reach out.

---

**Note:** This analysis is based on historical data and should be considered alongside other business factors when making operational decisions.
