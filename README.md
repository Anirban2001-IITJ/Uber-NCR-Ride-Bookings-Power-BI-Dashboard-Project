# Uber-NCR-Ride-Bookings-Power-BI-Dashboard-Project

## 📌 Project Overview

This Power BI project analyzes **150,000 Uber ride bookings** across the **National Capital Region (NCR)** from **January–December 2024**.

The dashboard uncovers patterns in booking behavior, cancellations, vehicle preferences, revenue generation, ride quality, and payment methods to provide actionable business insights.

---

## Dashboard Preview

![Dashboard Preview](Dashboard.gif)

---

## 📂 Dataset

| Attribute | Details |
|----------|----------|
| File | `ncr_ride_bookings.csv` |
| Records | 150,000 |
| Time Period | Jan 2024 – Dec 2024 |
| Features | 21 Columns |

### Key Columns

- Date, Time → Booking timestamp  
- Booking ID, Customer ID → Unique identifiers  
- Booking Status → Completed / Driver Cancelled / Customer Cancelled / No Driver Found / Incomplete  
- Vehicle Type → Auto, Go Mini, Go Sedan, Bike, Premier Sedan, eBike, Uber XL  
- Pickup & Drop Locations  
- Avg VTAT & CTAT  
- Booking Value  
- Ride Distance  
- Driver Rating & Customer Rating  
- Payment Method  
- Cancellation Reasons  

---

# 📊 Dashboard Highlights

## 1. Booking Status Breakdown

| Status | Count | Share |
|--------|-------|------|
| ✅ Completed | 93,000 | 62% |
| ❌ Driver Cancelled | 27,000 | 18% |
| ❌ Customer Cancelled | 10,500 | 7% |
| 🔍 No Driver Found | 10,500 | 7% |
| ⚠️ Incomplete | 9,000 | 6% |

**Insight:** Driver cancellations are the largest operational challenge.

---

## 2. Vehicle Type Distribution

| Vehicle | Rides |
|---------|------|
| Auto | 37,419 |
| Go Mini | 29,806 |
| Go Sedan | 27,141 |
| Bike | 22,517 |
| Premier Sedan | 18,111 |
| eBike | 10,557 |
| Uber XL | 4,449 |

**Insight:** Budget rides dominate NCR demand.

---

## 3. Revenue & Ride Metrics

| Metric | Value |
|---------|------|
| Total Booking Value | ₹5.18 Crore |
| Average Fare | ₹508 |
| Fare Range | ₹50–₹4,277 |
| Avg Distance | 24.6 km |
| Avg VTAT | 8.5 min |
| Avg CTAT | 29.1 min |

---

## 4. Ratings

| Metric | Score |
|---------|------|
| Driver Rating | 4.23 / 5 |
| Customer Rating | 4.40 / 5 |

---

## 5. Payment Method Preference

| Method | Usage |
|---------|------|
| UPI | 45% |
| Cash | 25% |
| Uber Wallet | 12% |
| Credit Card | 10% |
| Debit Card | 8% |

**Insight:** UPI is the dominant payment mode.

---

## 6. Cancellation Analysis

### Customer Cancellation
- Wrong Address

### Driver Cancellation
- Customer-related issue

### Incomplete Ride Reasons
- Vehicle Breakdown
- Customer Demand
- Medical Emergency

---

# 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard Development |
| Power Query | Data Cleaning |
| DAX | KPI Measures |
| CSV | Data Source |

---

# 📈 Key Business Insights

- Driver cancellations are **2.5×** customer cancellations.
- Auto + Go Mini generate **45% of ride demand**.
- UPI dominates digital payments.
- CTAT of **29 min** indicates customer wait-time concerns.
- Revenue exceeds **₹5.18 Crore annually**.

---

# 🗂️ Project Structure

```plaintext
Uber-NCR-Dashboard/
│
├── 📊 Uber.pbix
├── 📄 ncr_ride_bookings.csv
├── 🖼️ Dashboard.gif
└── 📝 README.md
```

---

# How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Uber-NCR-Dashboard.git
```

### Open in Power BI

1. Open `Uber.pbix`
2. Update CSV path
3. Refresh Data
4. Explore Dashboard

---

# 📌 Future Improvements

- Ride Demand Forecasting
- Interactive Geo Maps
- Driver Analytics
- Real-Time Dashboard
- Cancellation Prediction

---

# 👤 Author

**Anirban Paul**  
M.Sc. Digital Humanities & Computing  
IIT Jodhpur  

📧 anirbanpaul7800@gmail.com  

---

⭐ If you found this project useful, give it a star.
