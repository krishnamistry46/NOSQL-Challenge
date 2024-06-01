# NOSQL-Challenge
Module 12- NoSQL Challenge
# UK Food Standards Analysis - NoSQL Challenge

This repository contains crucial components for the NoSQL Challenge, focused on the analysis of UK food standards data using MongoDB. The challenge involves leveraging MongoDB, with key steps outlined below:

## Files:

- **NoSQL_setup_starter.ipynb:** Jupyter notebook for database setup and initial queries.
- **NoSQL_analysis_starter.ipynb:** Jupyter notebook for exploratory analysis queries.

## Key Procedures:

### Database Setup:

1. **Data Import:** Import `establishments.json` into MongoDB with the database named `uk_food` and the collection named `establishments`.
2. **Validation:** Confirm the database setup, list available databases and collections, and display a representative sample document.

### Database Updates:

1. **Data Enhancements:** Add data for "Penang Flavours," update BusinessTypeID, and remove establishments in Dover.
2. **Data Standardization:** Convert string values to numerical formats for latitude, longitude, and RatingValue.

### Exploratory Analysis:

1. **Data Queries:** Answer critical questions regarding hygiene scores, highly rated London establishments, top-rated places near "Penang Flavours," and local authorities with a hygiene score of 0.
