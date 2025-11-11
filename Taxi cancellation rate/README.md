

---

## 🚖 Taxi Cancellation Case Analysis

A KNIME-based data analysis project exploring taxi booking and cancellation trends.
The dataset was cleaned (missing values replaced, dates formatted) and analyzed to calculate the **daily cancellation rate**, then visualized using a **line plot**.
Results show that cancellation rates fluctuate over time, with noticeable spikes on certain dates.

---

### 📂 Dataset

**File:** `Taxi-cancellation-case.csv`
Contains information about taxi bookings, including:

* Booking dates
* Pickup and destination details
* Cancellation status (`Car_Cancellation`)

---

### 🧹 Data Cleaning

Performed using **KNIME Analytics Platform**:

* Removed or replaced missing values with `0` and `"Unknown"`
* Converted the `from_date` column from string to date format (`M/d/yy`)
* Ensured consistent data types for numerical and categorical columns

---

### 📊 Analysis

Goal: **Find the cancellation rate per date**

Steps performed:

1. Grouped the data by `from_date`
2. Calculated the average of `Car_Cancellation` to obtain the daily cancellation rate
3. Visualized the trend using a **Line Plot**

---
### 🖼️ Preview
<img width="1262" height="252" alt="image" src="https://github.com/user-attachments/assets/0cb1a014-fa0b-41af-899e-ef3afcda3c11" />

### 📈 Results & Insights

* The average cancellation rate **fluctuates over time**
* Certain dates show **noticeable spikes**, possibly due to external factors like demand surges or scheduling patterns
* The line plot helps highlight overall patterns in taxi service reliability

---
### 💾 Exported Files

* `TaxiAnalysis.csv` — cleaned dataset with daily cancellation rates
* `Taxi_Cancellation_Analysis.knwf` — KNIME workflow file

---

### 🔧 Tools Used

* **KNIME Analytics Platform**

  * CSV Reader
  * Missing Value
  * String to Date&Time
  * GroupBy
  * Line Plot

---

### 👤 Author

**Stevin Allen James**
Informatics Student — Universitas Kristen Petra

---


