<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=00BFFF&height=200&section=header&text=Hotel%20Booking%20Intelligence&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35" alt="Header" />

  <br />

  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Seaborn-Visualization-41CD52?style=for-the-badge&logo=python&logoColor=white" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Status-Complete-success?style=for-the-badge" alt="Status"/>

  <h3>🔍 Cracking the Cancellation Code: A Data-Driven Approach to Revenue Optimization</h3>

  <p>
    <a href="#-business-problem">Problem</a> •
    <a href="#-data-analysis">Analysis</a> •
    <a href="#-key-insights">Insights</a> •
    <a href="#-strategic-recommendations">Strategy</a> •
    <a href="#-technologies">Tech Stack</a>
  </p>
</div>

---

## 💼 Business Problem

**The Challenge:**
In recent years, both **City Hotels** and **Resort Hotels** have faced alarming cancellation rates (approx. **37%**). This phenomenon has led to:
* 📉 Diminished Revenue Generation.
* 🏨 Sub-optimal Hotel Room Utilization.
* 🛑 Operational Inefficiencies.

**The Goal:**
This project aims to analyze booking data to identify the root causes of cancellations and propose actionable, data-backed strategies to reduce churn and maximize **ADR (Average Daily Rate)**.

---

## 📊 Data Analysis Pipeline

We employed a rigorous data science workflow to extract value from the raw booking data:

1.  **Data Ingestion & Cleaning:** Handling null values, formatting dates, and filtering outliers (e.g., removing ADR > 5000).
2.  **Exploratory Data Analysis (EDA):** Uncovering patterns in pricing, seasonality, and customer demographics.
3.  **Hypothesis Testing:** Validating assumptions regarding price sensitivity and booking channels.
4.  **Visualization:** Creating intuitive charts to communicate findings to stakeholders.

---

## 💡 Key Insights

### 1. The Price Sensitivity Paradox
<div align="center">

</div>

* **Observation:** There is a direct positive correlation between higher ADR (Average Daily Rate) and cancellation rates.
* **Impact:** Customers are highly price-sensitive. When prices spike, the probability of cancellation increases significantly.
* **Context:** Resort hotels are generally more expensive and prone to fluctuations compared to City hotels.

### 2. The "Portugal" Problem
<div align="center">

</div>

* **Observation:** **Portugal (PRT)** accounts for a staggering **70%** of all cancellations.
* **Impact:** This indicates a specific localized issue, potentially related to service quality perceptions, local competitor pricing, or duplicate booking habits in that region.

### 3. Seasonality & Booking Channels
* **Peak Stress:** August sees the highest volume of both confirmed and canceled reservations.
* **The January Slump:** January experiences the highest *rate* of cancellations relative to bookings.
* **Channel Dependence:** **46%** of customers originate from Online Travel Agencies (OTAs), while only **4%** book directly. This high dependency on OTAs increases cancellation risk due to lenient cancellation policies.

---

## 🚀 Strategic Recommendations

Based on the data analysis, the following strategies are recommended to the management team:

| Strategy | Actionable Step | Expected Outcome |
| :--- | :--- | :--- |
| **Dynamic Pricing** | Implement dynamic pricing strategies to lower rates for specific hotels based on location and demand probability. | 🔻 Reduce price-driven cancellations. |
| **Weekend & Holiday Discounts** | Offer targeted discounts for Resort Hotels during weekends and holidays where cancellation probability is highest. | 📈 Increase occupancy rates during high-risk periods. |
| **The "January" Campaign** | Launch aggressive marketing campaigns in January with reasonable pricing tiers. | 💰 Mitigate revenue loss during the highest cancellation month. |
| **Quality Control (PRT)** | Investigate and improve service quality specifically in the Portugal region. | 🇵🇹 Lower the disproportionately high churn rate in the top market. |

---

## 🛠 Technologies Used

* **Python:** Core programming language.
* **Pandas:** Data manipulation and aggregation.
* **Matplotlib & Seaborn:** High-impact data visualization.
* **Jupyter Notebooks:** Interactive development environment.

---

## 🏁 Getting Started

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/yourusername/hotel-booking-analysis.git](https://github.com/yourusername/hotel-booking-analysis.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Run the notebook:**
    Open `Data Analysis (Hotel Booking).ipynb` in Jupyter or VS Code.

---

<div align="center">
  <p><i>"Data is the new oil, but intelligence is the engine."</i></p>
  
  <a href="https://github.com/Jagannath8260">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github" alt="Github"/>
  </a>
</div>
