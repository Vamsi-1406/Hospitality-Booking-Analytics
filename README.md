# 🏨 Hospitality Booking Analytics  
### End-to-End Data Analysis Project using Python & Power BI  
**Author:** Vamsi  
**Years Analyzed:** 2015–2017  
**Tools:** Python, Pandas, Seaborn, Matplotlib, Power BI

---

## 📌 Project Overview  
This project analyzes hotel booking data from 2015–2017 to uncover trends in guest behavior, pricing, seasonality, and cancellations.  
Insights were generated using Python (EDA + visualization), and a professional multi-page dashboard was built in Power BI.

The goal is to showcase real-world data analytics skills including:  
- Data cleaning & preprocessing  
- Exploratory data analysis  
- Visual storytelling  
- Business insights  
- Dashboard development  

---

## 📊 Key Insights

### 🔹 **1. OTA Dependency & Cancellation Risk**
- **59%** of all bookings come from Online Travel Agencies (OTAs)  
- OTAs contribute to **76%** of all cancellations  
- OTA cancellation rate ≈ **35%**  
➡️ Major revenue risk + forecasting instability

---

### 🔹 **2. ADR (Pricing) Seasonality**
- Lowest ADR in **January: $70.05**  
- Highest ADR in **August: $150.88**  
➡️ Strong seasonal demand → pricing optimization opportunity

---

### 🔹 **3. Lead Time Predicts Cancellation**
- Bookings made **300+ days ahead** cancel at **45–87%**  
- Short lead-time (<150 days) bookings are more reliable  
➡️ Long-term bookings = high-risk

---

### 🔹 **4. Guest Loyalty is Very Low**
- Only **~4%** of guests are repeated visitors  
➡️ Low return customer rate increases volatility

---

### 🔹 **5. ADR by Stay Duration**
- 1–3 night stays → **highest ADR ($96–$111)**  
- Peak ADR at **6 nights: $122.30**  
➡️ Short stays pay premium; long stays have moderate rates

---

## 🧠 Business Value Delivered  
This project answers several real hotel business questions:

- How much revenue is at risk from cancellations?  
- Which booking channels are most profitable?  
- When should hotels raise or lower prices?  
- How do booking behaviors differ by lead time or segment?  
- Which customer types contribute to higher stability and revenue?

---

## 📁 Project Structure  

hospitality_booking_analytics/
│
├── notebooks/
│ └── hotel_booking_analysis.ipynb
│
├── visuals/
│ ├── monthly_bookings.png
│ ├── cancellation_rate.png
│ ├── lead_time_cancellation.png
│ ├── adr_by_month.png
│ ├── adr_by_segment.png
│ ├── top_countries.png
│ └── adr_by_stay_length_line.png
│
├── powerbi/
│ └── hospitality_dashboard.pbix
│
└── README.md



---

## 📘 Tools & Technologies Used
- **Python**: pandas, numpy, seaborn, matplotlib  
- **Jupyter Notebook** for EDA  
- **Power BI** for interactive reporting  
- **GitHub** for version control & presentation  

---

## 📈 Dashboard Pages

### **Page 1 – Executive Summary**
- Total bookings, cancellations, cancellation rate, ADR  
- Monthly demand & ADR trends  
- Top countries  

### **Page 2 – Booking Behavior**
- Market segment cancellation rates  
- Lead time cancellation analysis  
- OTA share & behavior KPIs  

### **Page 3 – Revenue Insights**
- ADR by hotel type  
- ADR by stay duration  
- Revenue behavior summaries  

---

## 🚀 How to Run This Project

### 1. Download the notebook  
Open `notebooks/hotel_booking_analysis.ipynb`

### 2. Install dependencies  

### 3. Run all cells to generate visuals  
Images will be saved into the `visuals/` folder.

### 4. Open the Power BI dashboard  
Load:  
