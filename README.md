# 🏨 Hotel Booking Analysis

This project involves a comprehensive analysis of hotel booking data using Python in a Jupyter Notebook. It aims to discover patterns and trends in bookings, cancellations, customer types, lead times, and seasonal demand. The insights derived from this analysis can help hotels improve revenue management and customer satisfaction.

## 📊 Dataset Information

The dataset used is a popular public dataset for hotel bookings. It contains real-world data from two types of hotels: a city hotel and a resort hotel.

**Key Columns in the Dataset:**

- `hotel` – Type of hotel (City or Resort)
- `is_canceled` – Whether the booking was canceled (1) or not (0)
- `lead_time` – Number of days between booking and arrival
- `arrival_date_year`, `month`, `day_of_month`
- `stays_in_weekend_nights`, `stays_in_week_nights`
- `adults`, `children`, `babies`
- `meal`, `country`, `market_segment`, `distribution_channel`
- `is_repeated_guest`, `previous_cancellations`
- `reserved_room_type`, `assigned_room_type`
- `deposit_type`, `agent`, `company`, `customer_type`
- `adr` (Average Daily Rate), `required_car_parking_spaces`
- `total_of_special_requests`

- ## ⚙️ Requirements

To run this project, make sure you have the following Python libraries installed:

pandas
numpy
matplotlib
seaborn

## 🚀 How to Run

1->Clone this repository or download the notebook.
2->Launch Jupyter Notebook:
3->Open the Hotel booking.ipynb file.
4->Run each cell in order to execute the full analysis.

## 📌 Key Analysis & Visualizations

**The notebook includes:**

->Data Cleaning & Preprocessing
->Exploratory Data Analysis (EDA)
->Visualizations using Seaborn & Matplotlib

**Insights:**

->Resort hotels have fewer cancellations than city hotels.
->Most bookings are made via online travel agents (OTAs).
->Longer lead times are associated with higher cancellations.
->Booking behavior varies by month and customer type.
->Special requests and deposit types influence cancellations.

**Visualizations Include:**

->Bar plots showing cancellation distribution
->Pie charts of hotel types and market segments
->Heatmaps showing correlation between features
->Time series plots for monthly booking trends

## 🙌 Contributing
Contributions are welcome! Feel free to fork this repository and open a pull request with enhancements or additional analyses.

## 📄 License
This project is licensed under the MIT License.

## 👨‍💻 Author
Khushi Singh
📧 khushisingh101430@gmail.com
📅 Last Updated: August 2025
