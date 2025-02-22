# Flight-Booking-Prediction

Project Workflow:-

1️⃣ EDA & Data Cleaning

- Loaded the customer booking dataset from a CSV file.
- Checked data types, missing values, and unique values.
- Mapped categorical variables (e.g., flight_day was converted from text to numerical format).
- Identified and removed duplicate rows to improve data quality.
- Performed univariate analysis to visualize numerical feature distributions.
- Saved the cleaned dataset for further modeling.

2️⃣ Model Development-

- Preprocessing

i) Loaded the cleaned dataset.
ii) Checked for missing values (ensured data completeness).
iii) Encoded categorical variables using Label Encoding.

-Feature Selection & Splitting

i) Defined features (X) and target variable (y) where:
                Target: booking_complete (whether the customer completed a booking).
                Features: Other relevant customer attributes.
ii)Split the dataset into training (80%) and testing (20%) sets.

- Model Training
i) Implemented a Random Forest Classifier to predict customer bookings.
ii) Tuned hyperparameters for better model performance.

- Evaluation
i) Measured accuracy using classification report, confusion matrix, and accuracy score.
ii) Assessed model performance to determine how well it predicts bookings.
