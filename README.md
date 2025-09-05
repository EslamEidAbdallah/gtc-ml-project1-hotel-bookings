Hotel Bookings Data Analysis & Cancellation Prediction
This project focuses on analyzing hotel booking data, cleaning and transforming
Project Overview
The workflow includes:

Exploratory Data Analysis (EDA)

Previewed dataset structure (head, describe, info).
Visualized missing values using missingno and heatmaps.
Detected outliers using boxplots and the IQR method.


Data Cleaning & Feature Engineering

Handled missing values:
company, agent → replaced with 0
country → filled with the most frequent value (mode).
children → filled with the median value.
    
Removed duplicates and handled outliers (adr, lead_time).
Converted reservation_status_date to datetime.
Created new features:
total_guests
total_nights
is_family
One-hot encoded low-cardinality categorical columns.
Frequency encoded high-cardinality column (country).
Mapped months to numeric values.

Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn, Missingno
Scikit-learn (train_test_split)
