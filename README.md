✈️ Flight Delay Prediction — 2024 U.S. Flight Performance Analysis

This project performs a complete exploratory data analysis (EDA) and machine-learning–based prediction of U.S. flight delays using the 2024 Department of Transportation flight dataset, containing over 7 million flight records.

The project explores trends, identifies delay patterns, and builds predictive models to assist airlines, airports, and analysts in understanding operational inefficiencies.

📂 Dataset Overview

Source: U.S. DOT (2024 flight records)

Period: January 1 – December 31, 2024

Total Records: 7,079,081 flights

Number of Features: 35

Includes:

Airline/operator info

Flight numbers

Origin & destination

Scheduled vs actual departure/arrival

Delay cause codes

Taxi times

Distance

Cancellations & diversions

🔍 Dataset Snapshot

📊 Summary Statistics

📈 Key Findings
✈️ Average Arrival Delay by Month (2024)

Peak delays occur June–August (summer season).

February and November show the lowest averages.

🛫 Top 10 Busiest Origin Airports (2024)

ATL, DFW, and DEN handle the highest number of flights.

These hubs also show high operational load → higher delay risk.

❌ Flight Cancellation Reasons (2024)

B (Weather-related) is the most common cause.

A (Carrier issues) ranks second.

C (NAS/ATC delays) also contribute significantly.

🧠 Machine Learning Models
✔ Logistic Regression

Accuracy: 92.05%

Weak on minority class (delays > 15 minutes) due to class imbalance.

✔ Random Forest

Running on large dataset (results pending)

Expected: Higher recall on delayed flights

🔧 Tools & Technologies

Python

Pandas, NumPy

Matplotlib/Seaborn

Scikit-learn

Jupyter Notebook
