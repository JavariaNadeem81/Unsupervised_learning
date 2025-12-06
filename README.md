Customer Segmentation Project
Overview

This project uses KMeans clustering to segment customers based on Age and Behavioral Data (policy1–policy5).
The goal is to identify distinct customer segments to support marketing, product, and engagement strategies.

Methodology

Data Preprocessing:

Encoded categorical behavioral data using One-Hot Encoding

Scaled all features using StandardScaler

Clustering:

Applied KMeans clustering

Determined 5 clusters using the Elbow Method

Evaluation:

Silhouette Score used to evaluate cluster quality

Cluster Insights
Cluster	Age Profile	Behavioral Pattern	Key Insights
0	Mid-age (35–40)	policy3 & policy5	Stable customers; target with loyalty programs
1	Young (25–30)	policy1	Early adopters; ideal for awareness campaigns
2	Older (40–45)	policy2 & policy4	Moderate engagement; focus on personalized content
3	Mixed, younger	policy3	Price-sensitive; respond to promotions
4	Older (50+)	policy5	High-value; premium offerings & personalized service
Key Takeaways

Tailor marketing campaigns to each segment

Offer bundles and promotions based on behavior

Focus retention efforts on high-value clusters

Engage younger clusters to increase lifetime value