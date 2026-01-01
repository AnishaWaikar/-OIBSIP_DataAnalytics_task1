# -OIBSIP_DataAnalytics_task1
📱 Android App Market Analysis — README
🎯 Objective

The objective of this task was to analyze the Android app ecosystem using publicly available datasets to understand how app categories, user ratings, installs, pricing, and user sentiment influence app performance and market positioning. The focus was on transforming raw app metadata and review text into meaningful insights that highlight market dynamics and help identify factors that contribute to app visibility and user reception.

📝 Steps Performed

Data Loading & Inspection

Loaded apps.csv and user_reviews.csv datasets

Checked dataset shapes, previewed samples, validated column types

Data Cleaning & Preparation

Converted Installs, Price, and Size into numeric formats

Standardized Size into MB and cleaned pricing symbols

Removed duplicate listings based on App and Category

Dropped rows with missing critical values like Rating

Converted Rating to numeric for accurate analysis

Exploratory Insights

Visualized category-wise app distribution to identify competitive vs niche areas

Plotted rating distribution to observe quality thresholds

Analyzed installs vs price to explore user willingness to pay

Sentiment Analysis Integration

Calculated sentiment polarity scores from user reviews using TextBlob

Merged sentiment data with app metadata to correlate perception and rating

Insight Extraction

Identified price–sentiment trends and category-wise market patterns

Highlighted quality thresholds associated with install growth

🛠 Tools Used

Languages & Libraries: Python, Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Text Processing: TextBlob

Data Sources: apps.csv, user_reviews.csv

📌 Outcome (Brief)

The analysis revealed meaningful patterns about the Android app market. Competitive categories like Games and Family offer reach but require strong differentiation, while niche categories show opportunity for visibility with less competition. Maintaining a rating near 4.2 or above appears to support install growth, while pricing alone does not guarantee better perception — users evaluate experience first. Integrating sentiment with ratings confirmed that user mood and star ratings are related but not identical, emphasizing the importance of quality and retention before monetization.
