# AI Marketing Intelligence System for Amazon Product Reviews

## Project Description

This project is an AI-based marketing decision system built for the AI for Marketing Decisions final exam. The system uses Amazon product review data to analyze customer behavior, understand customer satisfaction, segment customers, predict positive reviews, recommend products, and support better marketing decisions.

The project combines Python, machine learning, natural language processing, and Power BI dashboarding. The final result is a marketing intelligence system that can help managers understand customer opinions, product performance, and AI-based marketing opportunities.

## Group Members

- Alimzhan Tursynov
- Sultan Mykhtybayev

## Dataset

The project uses the Amazon Product Reviews dataset.

Dataset source:  
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

The dataset includes customer reviews, product IDs, user IDs, review scores, review text, helpfulness information, and review dates.

Main columns used:

- Id
- ProductId
- UserId
- ProfileName
- HelpfulnessNumerator
- HelpfulnessDenominator
- Score
- Time
- Summary
- Text

## Tools and Libraries

The following tools and libraries were used in this project:

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TextBlob
- WordCloud
- Power BI
- GitHub

## Project Structure

```text
ai-marketing-project/
│
├── data/
│   ├── powerbi_reviews.csv
│   ├── powerbi_customer_segments.csv
│   ├── powerbi_recommendations.csv
│   ├── powerbi_product_performance.csv
│   ├── powerbi_sentiment_sample.csv
│   ├── powerbi_segment_strategy.csv
│   └── powerbi_recommendation_strategy.csv
│
├── notebook/
│   └── Final Exam Marketing.ipynb
│
├── dashboard/
│   ├── page1_executive_overview.png
│   ├── page2_customer_segmentation.png
│   ├── page3_predictive_analytics.png
│   ├── page4_recommendation_dashboard.png
│   ├── page5_product_performance.png
│   ├── page6_sentiment_analysis.png
│   ├── page7_ethics_privacy_risk.png
│   └── page8_ai_marketing_strategy.png
│
├── presentation/
│   └── Final Exam Marketing Presentation.pptx
│
├── report/
│
└── README.md
