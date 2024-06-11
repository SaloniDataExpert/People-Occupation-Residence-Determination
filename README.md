# People Occupation/Residence Determination

## Overview
This project aims to determine the occupation and residence locations of people using location data collected at 30-minute intervals from a MongoDB database. The data includes continuous latitude and longitude points, providing a detailed trajectory of each rider's movements. By analyzing these location patterns, we can infer the key places where riders spend most of their time, such as their workplace and home.

## Objectives
- **Data Collection**: Extract and preprocess rider location data from MongoDB.
- **Data Analysis**: Use geospatial analysis techniques to process continuous latitude and longitude data.
- **Pattern Identification**: Identify patterns in the data to determine the primary locations of occupation and residence for each rider.
- **Model Development**: Develop and implement models to accurately classify occupation and residence locations based on the analyzed data.
- **Validation**: Validate the model's accuracy and refine the approach as needed.

## Dataset Details
- **Data Source**: MongoDB database
- **Frequency**: Location data collected every 30 minutes
- **Data Points**: Continuous latitude and longitude coordinates for each rider

## Methodology
1. **Data Extraction**: Extract raw location data from the MongoDB database.
2. **Data Preprocessing**: Clean and preprocess the data to remove any inconsistencies or noise.
3. **Geospatial Analysis**: Utilize geospatial analysis techniques to map out the trajectories and identify clusters of locations.
4. **Pattern Recognition**: Apply clustering algorithms to recognize patterns and frequent locations in the data.
5. **Model Training**: Train models to classify key locations as occupation or residence.
6. **Model Validation**: Validate the model's performance using a subset of data and refine it for better accuracy.

## Tools and Technologies
- **Database**: MongoDB
- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Geopandas, Matplotlib
- **Techniques**: Geospatial analysis, Clustering algorithms, Machine Learning
