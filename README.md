# Hotel Booking Cancellation Analysis

Exploratory data analysis of City Hotel and Resort Hotel booking cancellations — identifying key drivers of cancellations (price, lead time, booking channel, country of origin) and providing business recommendations to reduce lost revenue.

## Business Problem

In recent years, City Hotel and Resort Hotel have seen high cancellation rates. Each hotel is now dealing with a number of issues as a result, including reduced revenue and less-than-ideal room utilization. Lowering cancellation rates is therefore a primary goal for both hotels — to increase efficiency in generating revenue.

This project analyzes hotel booking cancellations, along with other contributing factors, to understand their impact on yearly revenue generation and to offer data-driven recommendations.

## Research Questions

1. What are the variables that affect hotel reservation cancellations?
2. How can we make hotel reservation cancellations lower?
3. How will hotels be assisted in making pricing and promotional decisions?

## Hypotheses

1. More cancellations occur when prices are higher.
2. When there is a longer waiting list, customers tend to cancel more frequently.
3. The majority of clients come from offline travel agents to make their reservations.

## Dataset

- **Source:** [Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) (Kaggle), covering bookings from 2015–2017 for one City Hotel and one Resort Hotel.
- **File:** `data/hotel_bookings.csv`
- Not redistributed in this repo if licensing restricts it — download it from the source link above and place it in `data/` before running the notebook.

## Repository Structure

```
hotel-booking-cancellation-analysis/
├── README.md
├── report/
│   └── Hotel_Cancellation_Analysis_Report.md
├── notebook/
│   └── hotel_booking_cancellation_analysis.ipynb
├── data/
│   └── hotel_bookings.csv       
└── images/
    └── (exported chart PNGs referenced in the report)
```

## Key Findings

- **37%** of reservations were cancelled — a significant share of total bookings, with a material impact on hotel earnings.
- **City Hotel** receives more bookings overall than Resort Hotel; Resort Hotel tends to command a higher average daily rate (ADR).
- **August** has both the highest number of confirmed and the highest number of cancelled reservations; **January** has the highest cancellation rate relative to bookings.
- **Price is a leading driver of cancellations** — the average daily rate for cancelled bookings is consistently higher than for bookings that were kept, and this gap widens over time (2016–2017).
- **Portugal (PRT)** is the top country by number of cancellations (70.07% share among top-cancelling countries), followed by Great Britain (GBR) and Spain (ESP).
- **Booking channel:** ~46% of clients book through online travel agencies, ~27% through groups, and only ~4% book directly with the hotel.

## Recommendations

1. **Pricing strategy:** Since cancellation rates rise with price, hotels should review and adjust pricing strategies — particularly for higher-priced periods — to reduce the incentive to cancel.
2. **Weekend/holiday discounts:** Resort Hotel shows a higher cancellation-to-non-cancellation ratio than City Hotel; offering reasonable discounts on weekends or holidays could help close this gap.
3. **Targeted January campaigns:** January has the highest cancellation volume — hotels could run targeted marketing or retention campaigns during this month to protect revenue.
4. **Service quality investment:** Increasing service quality, particularly in Portugal (the top cancelling market), may help reduce cancellation rates in that segment.

See [`report/Hotel_Cancellation_Analysis_Report.md`](report/Hotel_Cancellation_Analysis_Report.md) for the full write-up with supporting charts, and [`notebook/hotel_booking_cancellation_analysis.ipynb`](notebook/hotel_booking_cancellation_analysis.ipynb) for the analysis code.

## Tools Used

- Python (pandas, numpy)
- matplotlib / seaborn
- Jupyter Notebook



## Author

* Nithin K N
*  https://www.linkedin.com/in/nithin-k-n-/
*  knnithin02@gmail.com 

