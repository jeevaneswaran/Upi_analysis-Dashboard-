# UPI Transactions Dashboard
I developed a comprehensive project in Excel, creating multiple dashboards and tables to analyze UPI transaction data. This involved data preprocessing, data cleaning, and data visualization.
A real-time overview of UPI (Unified Payments Interface) transaction data, built in Microsoft Excel using PivotTables, PivotCharts, slicers, and conditional formatting. The dashboard provides a 360° view of transaction volume, value, success/failure rates, fraud detection, and behavioral patterns across banks, apps, states, and time.
![Dashboard Preview](output.png)
---
📁 Repository Contents
```
├── Upi_analysis-Dashboard.xlsx     # Main Excel dashboard file
├── png/
│   └── phonepay_raw_data.xlsx      # Anonymized raw transaction dataset
├── assets/
│   └── p1.png                      # Dashboard screenshot
└── README.md
```
---
🧾 About the Data
Field	Details
Source	Real UPI transaction data (fully anonymized)
Privacy	No PII — names, phone numbers, UPI IDs excluded
Format	Excel (.xlsx)
Granularity	Transaction-level: amount, timestamp, bank, UPI app, merchant category, state, gender, status
> ⚠️ **Disclaimer:** Anonymized/aggregated for educational and portfolio purposes only. Not for commercial or production use.
---
🔧 Tools & Techniques
Microsoft Excel — PivotTables & PivotCharts
Slicers: City, Gender, Merchant Category, Merchant Name
Donut, line, bar, and heatmap-style charts
Filled Map chart (state-wise transaction amounts)
Conditional formatting for KPI highlighting
Calculated fields: success rate, fraud %, cashback
---
📈 Key Metrics (KPIs)
Metric	Value
Total Transactions	5,02,887
Total Amount (INR)	₹44.25 Cr
Total Cashback (INR)	₹34.63 L
Success Rate	91.00%
Suspected Fraud	17,089
---
📊 Visual Breakdowns
Visual	Shows
Amount Over Time (Daily)	Daily transaction value trend
By UPI App	App-wise market share
By Status	Success / Failed / Pending / Refunded split
By State	State-wise value on India map
By Bank	Bank-wise value comparison
By Transaction Type	P2M, P2P, Bill Pay, Shopping, etc.
By Hour	Peak usage hours
By Hour & Day	Heatmap of day × hour intensity
Filter Panel
Slicers for: City · Gender · Merchant Category · Merchant Name
---
💡 Key Insights
PhonePe leads UPI share at ~50%, followed by Google Pay (21.3%) and Paytm (14.3%)
91% success rate — 7% failure rate is the main improvement area
~3.4% suspected fraud rate (17,089 / 5,02,887 transactions)
Peak hours cluster in the evening — useful for load planning
Top states by value: Maharashtra, Karnataka, Delhi
P2M is the largest transaction type by value
---
🚀 How to Use
Clone the repo:
```bash
   git clone https://github.com/jeevaneswaran/Upi_analysis-Dashboard-.git
   ```
Open `Upi_analysis-Dashboard.xlsx` in Excel (2016+ recommended for full PivotTable/Slicer support).
Use the slicers to filter by City, Gender, Merchant Category, or Merchant Name.
Charts and KPIs update dynamically with your filter selections.
---
🛠️ Skills Demonstrated
Data cleaning & transformation
PivotTable/PivotChart dashboard design
KPI design & business metric calculation
Geographical (map) visualization
Time-series & heatmap analysis
Dashboard UX/filter design
---
📄 License
Licensed under the MIT License.
---
🙋 Author
Jeevaneswaran
📧 jeevaneswaran2004@gmail.com
🔗 LinkedIn
