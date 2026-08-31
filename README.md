# Upi_analysis-Dashboard-
I developed a comprehensive project in Excel, creating multiple dashboards and tables to analyze the data. This process involved several stages, including data preprocessing, data cleaning, and data visualization.
📊 UPI Transactions Dashboard
A real-time overview of UPI (Unified Payments Interface) transaction data, built in Microsoft Excel using PivotTables, PivotCharts, slicers, and conditional formatting. The dashboard provides a 360° view of transaction volume, value, success/failure rates, fraud detection, and behavioral patterns across banks, apps, states, and time.
![Dashboard Preview](assets/dashboard-preview.png)
---
📁 Repository Contents
```
├── Upi_analysis-Dashboard.xlsx   # Main Excel dashboard file
├── png/
│   └── phonepay_raw_data.mov.xlsx      # Anonymized raw transaction dataset
├── assets/
│   └── p1.png         # Dashboard screenshot
└── README.md
```
🧾 About the Data
Source: Real UPI transaction data (fully anonymized — no personally identifiable information such as names, phone numbers, or UPI IDs is included).
Format: CSV
Granularity: Individual transaction-level records including amount, timestamp, bank, UPI app, merchant category, state, gender, and transaction status.
> ⚠️ **Disclaimer:** This dataset has been anonymized/aggregated for educational and portfolio purposes. It does not represent any individual's real financial activity and should not be used for commercial or production decision-making.
---
🔧 Tools & Techniques Used
Microsoft Excel
PivotTables & PivotCharts
Slicers (City, Gender, Merchant Category, Merchant Name) for interactive filtering
Donut, line, bar, and heatmap-style charts
Filled Map chart for state-wise transaction amounts
Conditional formatting for KPI highlighting
Calculated fields for success rate, fraud detection %, and cashback
---
📈 Dashboard Features
Key Metrics (KPIs)
Total Transactions: 5,02,887
Total Amount (INR): ₹44.25 Cr
Total Cashback (INR): ₹34.63 L
Success Rate: 91.00%
Suspected Fraud: 17,089 transactions
Visual Breakdowns
Visual	Insight
Transactions Amount Over Time (Daily)	Daily trend of transaction value across the month
Transactions by UPI App	Market share — PhonePe (49.8%), Google Pay (21.3%), Paytm (14.3%), and others
Transactions by Status	Success (91%), Failed (7%), Pending (2%), Refunded (0%)
Transactions Amount by State	State-wise transaction value with an interactive map of India
Transactions Amount by Bank	Bank-wise comparison (HDFC, SBI, Kotak, Canara, ICICI, Axis, BoB, PNB)
Transactions Amount by Type	Breakdown across P2M, P2P, Bill Payment, Online Shopping, Recharge, Subscription, Wallet Transfer
Transactions Amount by Hour	Peak usage hours across the day
Transactions Amount by Hour & Day (Heatmap)	Combined day-of-week and hour-of-day intensity map
Filter Panel
Interactive slicers allow filtering the entire dashboard by:
City
Gender
Merchant Category
Merchant Name
---
💡 Key Insights
PhonePe dominates UPI transaction share at nearly 50%, followed by Google Pay and Paytm.
91% success rate indicates healthy platform reliability, with failures (7%) as the main area for improvement.
~3.4% suspected fraud rate (17,089 out of 5,02,887 transactions) highlights the need for stronger fraud monitoring.
Peak transaction hours cluster in the evening, useful for infrastructure/load planning.
Maharashtra, Karnataka, and Delhi lead in transaction value among states.
P2M (Person-to-Merchant) transactions form the largest transaction type by value.
---
🚀 How to Use
Clone this repository:
```bash
   git clone https://github.com/jeevaneswaran/Upi_analysis-Dashboard-.git
   ```
Open `phonepay_raw_data.mov.xlsx` in Microsoft Excel (2016 or later recommended for full PivotTable/Slicer support).
Use the slicers on the left panel to filter by City, Gender, Merchant Category, or Merchant Name.
All charts and KPIs will update dynamically based on your filter selections.
---
🛠️ Skills Demonstrated
Data cleaning & transformation
PivotTable/PivotChart-based dashboard design
KPI design and business metric calculation
Geographical (map) visualization
Time-series and heatmap analysis
Dashboard UX/filter design
---
📄 License
This project is licensed under the MIT License.
---
🙋 Author
[Your Name]
📧 jeevaneswaran2004@gmail.com
🔗 LinkedIn 
