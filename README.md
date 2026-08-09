# GenAI-Powered Customer Feedback Insights

## Project Overview

This project analyzes customer feedback from Amazon and Yelp reviews using Python and GenAI-assisted thematic analysis.

The objective is to transform unstructured customer reviews into meaningful business insights, identify recurring customer pain points and strengths, and provide actionable recommendations.

## Objectives

- Analyze customer sentiment
- Clean and validate customer-feedback data
- Identify positive and negative customer themes
- Compare Amazon and Yelp feedback
- Identify evidence-based root-cause hypotheses
- Prioritize customer problems
- Generate actionable business recommendations
- Demonstrate how GenAI can support customer-feedback analysis

## Dataset

The original dataset contains 2,000 customer reviews.

After data-quality checks:

- Original reviews: 2,000
- Duplicate rows removed: 14
- Final unique reviews: 1,986
- Missing values: 0
- Remaining duplicates: 0

### Final Dataset Distribution

| Source | Positive | Negative | Total |
|---|---:|---:|---:|
| Amazon | 493 | 497 | 990 |
| Yelp | 499 | 497 | 996 |
| **Total** | **992** | **994** | **1,986** |

## Key Insights

### Amazon

Amazon feedback is primarily product-oriented.

Major customer concerns include:

- Product usability and fit
- Audio and call quality
- Battery and charging
- Product reliability and durability
- Value for money
- Customer service/support

Customers also appreciate:

- Product quality and performance
- Sound/audio quality
- Battery performance
- Compatibility
- Value for money

### Yelp

Yelp feedback is primarily experience-oriented.

Major customer concerns include:

- Food quality and taste
- Service and staff
- Waiting time
- Value and pricing
- Overall customer experience
- Atmosphere/location

Customers also appreciate:

- Food quality
- Service
- Atmosphere
- Value
- Menu selection
- Overall experience

## Business Recommendations

### Amazon

Prioritize:

1. Product usability and fit
2. Audio and call reliability
3. Battery and charging performance
4. Product reliability and quality control
5. Customer-perceived value

### Yelp

Prioritize:

1. Food quality and consistency
2. Service and staff experience
3. Waiting-time reduction
4. Perceived value
5. Overall customer experience

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- GenAI-assisted analysis

## Project Structure

```text
GenAI-Customer-Feedback-Insights/
│
├── data/
│   ├── amazon_cells_labelled.txt
│   ├── yelp_labelled.txt
│   ├── capstone_customer_feedback.csv
│   ├── capstone_customer_feedback_clean.csv
│   ├── negative_reviews_for_genai.csv
│   └── positive_reviews_for_genai.csv
│
├── notebooks/
│   └── Customer_Feedback_Analysis.ipynb
│
└── README.md