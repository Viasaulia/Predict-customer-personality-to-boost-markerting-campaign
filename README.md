# ***Predict Customer Personality to Boost Markerting Campaign by Machine Learning***

Mengolah data historical marketing campaign guna menaikkan performa dan mentarget customer yang tepat agar dapat bertransaksi di platform perusahaan menggunakan clustering

## Data Cleaning and Data Preparation
1. Handling null value
2. Binning data
3. Feature engineering
   
   a. Create column Conversion Rate
   
   b. Create column Child (whether customer have kid or teen at home)
   
   c. Create dt_days_customer (how long customer used the platform since they first join)
4. Encode categorical value
5. Drop unused column

## Data Modelling
1. Reduce dimensionality with RFM analysis so we have column recency, total purchase, total spend as RFM and dt_days_customer and umur as L and C
2. Handling outlier of data
3. Scaling data
4. Find the optimal K with elbow method
5. Reduce dimensionality with PCA (use 2 components)
6. Clustering

## Customer Personality Analysis
Make new strategies for each cluster based on cluster behavior or personality
