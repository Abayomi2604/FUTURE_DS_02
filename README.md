## 📌 Project Overview
This project analyzes the performance of a social media marketing campaign using Power BI.  
The goal is to evaluate performance, engagement , **CTR (Click through Rate)** and **ROI (Return on Investment)** 
The analysis was built around key performance indicators (KPIs) and DAX measures, then visualized in an interactive Power BI dashboard.

---

## 🔑 Key Metrics
- **Total Impression** – the total number of times campaign ads were shown (served) to people.  
- **Average Engagement** – measures how much, on average, people interacted with your ad/content.  
- **Total Conversion** = the number of people who completed the desired action (purchase, signup, download, etc.).
- **ROI (%)** = `(Profit / Marketing Spend) * 100`  
- **Total Clicks (%)** = the sum of all recorded clicks in your campaign.

---

## ⚙️ DAX Measures Used
```DAX
Average Engagement = AVERAGE ('Data'[Total Engagement])
Total Clicks = SUM ('Data' [Clicks])
Total Impression = SUM ('Data' [Impression])
Total ROI (%) = SUM ('Data' [ROI])
Total conversion = SUM ('Data' [Conversion])
CTR % = DIVIDE([Total Clicks], [Total Impressions], 0)
Conversion Rate = DIVIDE([Total Conversions], [Total Clicks], 0)
```

---

## 📜 Key Results
- **1.1B Impressions**
- **110M Clicks**
- **8.8M Conversions**
- **Avg Engagement = 5.5**
- **Total ROI = 1.0M**
- **Influencer & Search campaigns had the strongest ROI**
- **Foodies and Tech enthusiast audiences drove the most engagement**

---

## 🖼️ Visualization

**Dashboard created in Power BI,** with:

- **KPI cards for overall performance**

- **ROI by Campaign Type**

- **CTR by Channel**

- **Engagement by Customer Segment**

- **Conversion trends over time**
  
- **Average Engagement by campaign type**

**(See screenshots folder for visuals)**

---

## 💡 Insights

- **The campaign generated a positive ROI, meaning revenue outweighed costs.**

- **Certain channels produced higher conversion rates, suggesting a need to reallocate budget.**

- **Seasonal trends showed spikes in revenue aligned with specific campaign pushes.**
