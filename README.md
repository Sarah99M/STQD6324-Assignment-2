# STQD6324-Assignment-2
![Airline Delay Analysis](image/airplane.png)

# Airline On-Time Performance Analysis (2005)

## Overview

This project analyzes U.S. domestic flight operations in the year 2005, focusing on **flight delays, cancellations, and route reliability**. Using Hive and Jupyter Notebook, the analysis extracts, cleans, and visualizes large-scale airline data to uncover operational inefficiencies and support decision-making for both airlines and passengers.

---

## Tools and Technologies

- **Hive SQL** – for scalable querying of large datasets
- **Jupyter Notebook** – for interactive analysis and visualization
- **Python libraries**:
  - `pandas` – data manipulation
  - `matplotlib` & `seaborn` – plotting and charts
  - `pyhive` – database connection to Hive

---

## Key Analytical Sections

### 1. Delay Pattern Analysis
- Explored average arrival delays by time of day, weekday, month, and season.
- Found that **midnight and summer flights have the highest average delays**, while **morning and spring flights are more punctual**.

### 2. Delay Factor Analysis
- Analyzed major causes of delays: carrier-related, NAS (air traffic), late aircraft, weather, and security.
- **Carrier delay and NAS delay** emerged as dominant contributors.

### 3. Cancellation Analysis
- Investigated monthly and seasonal cancellation trends.
- **Winter and Q1** showed the **highest cancellation rates**, likely due to weather disruptions.

### 4. Problematic Route Analysis
- Identified routes with more than 50 flights and the highest average arrival delays.
- Many problematic routes were connected to **Newark Airport (EWR)**, indicating operational or congestion issues.

### 5. Carrier Performance Evaluation
- Compared airlines by flight volume and average delay time.
- **AirTran (FL)** and **Alaska Airlines (AS)** had the longest average delays; **Hawaiian Airlines (HA)** performed best.

### 6. Problematic Flight Numbers
- Ranked individual flight numbers by frequency and delay.
- Highlighted high-risk flights for operational improvement and passenger awareness.

---

## Conclusion

- Flight delays and cancellations exhibit **clear patterns** across **time, location, and carriers**.
- **Certain airports (e.g., EWR) and routes consistently underperform**, pointing to structural bottlenecks.
- **Morning flights and spring travel are generally more reliable**, while **midnight flights and winter months pose higher risks**.

---

## Recommendations

### For Airlines:
- Optimize schedules for **early morning and winter flights**
- Monitor **high-delay airports and routes**, especially EWR-related connections
- Create a **flight risk scoring system** to guide resource allocation

### For Passengers:
- Prefer **morning flights** and **spring/fall travel**
- Avoid risky flight numbers and **midnight departures**
- Consider airline punctuality performance when booking (e.g., avoid FL/AS, favor HA/WN)

---

## 📁 File Structure
├── Assignment2_P146399.ipynb # Main Jupyter Notebook for the entire analysis
├── README.md # Project documentation 
