# 📊 Consumer Financial Complaints – Operations Dashboard

An interactive, multi-tab operations dashboard built with **Python + Plotly**, visualising **555,957 consumer complaints** filed with the U.S. Consumer Financial Protection Bureau (CFPB) between 2012 and 2015.

---

## 🚀 Live Dashboard

Open **`consumer_complaints_dashboard.html`** in any modern browser — no server or install needed.

---

## 📁 Files

| File | Description |
|------|-------------|
| `consumer_complaints_dashboard.html` | Self-contained interactive dashboard (open in browser) |
| `README.md` | This file |

---

## 📈 Dashboard Tabs

### 📋 Executive Overview
- **6 KPI cards** — Total complaints, timely response rate, dispute rate, monetary relief rate, median response time, companies count
- **Monthly complaint volume trend** (2012–2015 line chart)
- **Complaints by product category** (horizontal bar)
- **Company response type breakdown** (donut chart)

### 🏢 Company Performance
- **Timely response rate** for top 10 companies with 97% benchmark line (colour-coded green / orange / red)
- **Year-over-year complaint volume** by top 5 products (grouped bar chart)

### ⚙️ Operations & Channels
- **Submission channel breakdown** — Web, Referral, Phone, Postal Mail, Fax, Email
- **Consumer dispute rate by product** category

### 🗺 Geographic View
- **USA choropleth map** — complaint density shaded by state

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|--------|-------|
| Total Complaints | 555,957 |
| Timely Response Rate | 97.5% |
| Consumer Dispute Rate | 20.2% |
| Monetary Relief Rate | 6.9% |
| Median Response Time | 1 day |
| Companies Reported | 3,180 |
| Date Range | Jan 2012 – Dec 2015 |

---

## 🛠 Built With

- **Python 3** — data processing
- **pandas** — data wrangling
- **Plotly** — interactive charts (choropleth, bar, donut, line)
- **HTML / CSS / JS** — single-file self-contained dashboard

---

## 📂 Data Source

[CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/)
Data covers financial products including Mortgages, Debt Collection, Credit Reporting, Credit Cards, and more.

---

*Dashboard generated with Python + Plotly • CFPB Data 2012–2015*
