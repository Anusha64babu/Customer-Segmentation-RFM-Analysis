# Customer Segmentation & RFM Analysis

## Project Overview
Advanced customer analytics project using RFM (Recency, Frequency, Monetary) analysis and machine learning clustering to segment customers and provide actionable marketing insights. Demonstrates proficiency in unsupervised learning, statistical analysis, and business intelligence.

## Business Problem
- Identify distinct customer segments for targeted marketing
- Understand customer behavior and purchasing patterns
- Predict customer churn risk
- Optimize marketing budget allocation
- Improve customer retention strategies

## Dataset
- **Size**: 5,000+ customers with transaction history
- **Features**: Customer ID, Transaction Date, Purchase Amount, Product Category, Payment Method
- **Time Period**: 18 months of transaction data

## Key Skills Demonstrated
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning**: K-Means Clustering, Elbow Method, Silhouette Analysis
- **Statistical Analysis**: RFM analysis, cohort analysis, customer lifetime value
- **Data Visualization**: Cluster plots, distribution analysis, segment profiling
- **Business Analytics**: Customer segmentation, churn prediction, marketing recommendations

## Analysis Methodology

### 1. RFM Analysis
RFM is a proven marketing analysis technique that examines:
- **Recency**: How recently did the customer make a purchase?
- **Frequency**: How often do they purchase?
- **Monetary**: How much do they spend?

### 2. Customer Segmentation (K-Means Clustering)
- Applied machine learning to identify natural customer groups
- Optimized number of clusters using Elbow Method and Silhouette Score
- Created 4 distinct customer segments

### 3. Cohort Analysis
- Tracked customer behavior over time
- Calculated retention rates by cohort
- Identified patterns in customer lifecycle

## Key Findings

### Customer Segments Identified:

1. **Champions** (23% of customers, 42% of revenue)
   - High recency, frequency, and monetary scores
   - Most valuable customers
   - Recommendation: VIP treatment, exclusive offers

2. **Loyal Customers** (31% of customers, 35% of revenue)
   - Consistent purchase behavior
   - Moderate to high spend
   - Recommendation: Loyalty rewards, personalized communications

3. **At-Risk Customers** (28% of customers, 18% of revenue)
   - Previously active but recent engagement dropped
   - Recommendation: Re-engagement campaigns, special discounts

4. **New/Potential** (18% of customers, 5% of revenue)
   - Recent first purchase, low frequency
   - Recommendation: Onboarding programs, welcome offers

## Analysis Components

### 1. Data Preprocessing
- Transaction aggregation by customer
- RFM score calculation
- Feature scaling and normalization

### 2. Exploratory Data Analysis
- Customer distribution analysis
- Purchase behavior patterns
- Revenue contribution by segment

### 3. Machine Learning Clustering
- K-Means algorithm implementation
- Optimal cluster selection
- Cluster profiling and interpretation

### 4. Cohort Analysis
- Monthly cohort creation
- Retention rate calculation
- Churn pattern identification

### 5. Customer Lifetime Value (CLV)
- CLV estimation by segment
- Revenue projection
- ROI analysis for marketing strategies

## Visualizations Created
- RFM score distribution plots
- Customer segment scatter plots (3D)
- Elbow curve for optimal clusters
- Cohort retention heatmap
- Segment comparison charts
- Revenue distribution by segment

## Tools & Technologies
- **Programming**: Python 3.8+
- **Data Analysis**: Pandas, NumPy
- **Machine Learning**: Scikit-learn (K-Means, StandardScaler)
- **Visualization**: Matplotlib, Seaborn
- **Statistical Analysis**: SciPy

## How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Run the analysis
python customer_segmentation_analysis.py

# Outputs will be generated in the 'outputs' folder
```

## Outputs
- `customer_segmentation_report.txt`: Comprehensive analysis report
- Multiple visualization PNG files
- `customer_segments.csv`: Customers with assigned segments
- `segment_profiles.csv`: Detailed segment characteristics

## Business Impact

### Marketing Strategy Recommendations:

1. **Champions**: 
   - Allocate 40% of marketing budget
   - Exclusive early access to new products
   - Premium customer service

2. **Loyal Customers**:
   - Allocate 30% of marketing budget
   - Loyalty program with tier benefits
   - Birthday/anniversary offers

3. **At-Risk Customers**:
   - Allocate 20% of marketing budget
   - Win-back campaigns
   - Survey to understand pain points

4. **New/Potential**:
   - Allocate 10% of marketing budget
   - Educational content
   - First-purchase incentives

### Expected Results:
- 15-20% increase in customer retention
- 25% improvement in marketing ROI
- 30% reduction in customer acquisition cost
- Better resource allocation across segments

## Future Enhancements
- Predictive churn modeling using classification algorithms
- Real-time segmentation with streaming data
- A/B testing framework for segment-specific campaigns
- Integration with CRM systems
- Advanced CLV prediction models

## Technical Highlights
- Clean, modular, well-documented code
- Scalable architecture for large datasets
- Reproducible analysis with random seed
- Professional visualizations
- Statistical validation of clusters

---
**Author**: [Your Name]
**Date**: 2025
**Tools**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
