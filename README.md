📌 Project: E-commerce Funnel Analysis
📊 Overview

This project analyzes user behavior across an e-commerce purchase funnel to identify where users drop off before completing a purchase.
A synthetic dataset was designed to simulate real-world user events and enable controlled funnel analysis.

🎯 Business Question

Where do users drop off in the purchase funnel, and which stage shows the highest abandonment?

🧱 Funnel Steps

The funnel consists of the following user actions:

View Product

Add to Cart

Checkout

Purchase

📂 Dataset

Synthetic event-level dataset created for analysis purposes

500 unique users

Each row represents a user event within the funnel

Columns:

user_id: Unique user identifier

event: User action (funnel step)

🔍 Analysis Performed

Counted unique users at each funnel step

Calculated conversion and drop-off rates between steps

Visualized user drop-off using a bar chart

Interpreted results from a product and business perspective

📉 Key Findings

The funnel shows a consistent drop-off at each step

The largest drop-off occurs between the checkout and purchase stages

This suggests potential friction during the payment process

💡 Recommendations

Simplify the checkout and payment flow

Investigate possible issues such as payment complexity or trust signals

Consider A/B testing alternative checkout designs to reduce abandonment

🛠️ Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook (Kaggle)

📎 Notes

This project focuses on analytical thinking and funnel analysis rather than domain-specific expertise.
The dataset is synthetic and created solely for learning and demonstration purposes.
