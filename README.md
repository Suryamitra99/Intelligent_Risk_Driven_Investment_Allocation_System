# 💹 FinWise: Intelligent Risk-Driven Investment Allocation System

### Overview
**FinWise** is a Python-powered decision intelligence tool that helps investors design optimal investment portfolios based on risk tolerance, historical asset performance, and expected financial goals.  
The system combines **financial analytics, data visualization, and risk modelling** to forecast investment growth and suggest ideal portfolio allocations across multiple asset classes.

This project merges **data science principles** with **investment strategy** to create a transparent and intuitive investment planning framework.

---

### 🧠 Objectives
FinWise was developed to:
1. Enable **data-driven portfolio optimization** using historical asset returns.  
2. Classify investors by **risk profile** — from *very low* to *very high*.  
3. Forecast **investment growth** and visualize performance trends.  
4. Support **goal-based investing** by matching expected returns to suitable risk levels.

---

### ⚙️ Key Inputs
- **Starting Year** – Investment beginning year  
- **Final Year** – Target evaluation year  
- **Initial Investment** – Capital available at the start  
- **Investable Amount Per Annum (IAPA)** – Annual contribution amount  
- **IAPA Increment (%)** – Annual increment rate in investment  
- **Expected Return** – Desired final portfolio value  

---

### 📊 Key Outputs
1. **Optimal Portfolio Allocation** – Distribution across Bonds, Large-Cap, Mid-Cap, Small-Cap mutual funds, and Gold  
2. **Growth Forecast** – Year-wise cumulative investment and return growth  
3. **Risk Classification** – Categorization into risk tiers from *Very Low* to *Very High*  
4. **Data Visualization Dashboard** – Includes:
   - **Pie Chart:** Asset allocation breakdown  
   - **Stacked Bar Graph:** Investment and return progression  
   - **Tabular Summary:** Yearly cumulative values  

---

### 💡 Features
- **Adaptive Risk-Based Allocation:**  
  The algorithm dynamically adjusts exposure to high- and low-risk assets according to the user’s expected return.

- **Interactive Interface:**  
  Users can input their financial parameters and instantly view updated projections.

- **Comprehensive Visualization:**  
  Integrated charts and tables offer a holistic overview of financial performance.

- **Custom Portfolio Profiles (P1–P4):**  
  Predefined risk-based profiles that evolve from conservative (bond-heavy) to aggressive (equity-focused) allocations.

---

### 🧮 Technical Architecture
- **Computation Engine:**  
  Core algorithms developed in **Python**, leveraging libraries such as `pandas`, `numpy`, and `matplotlib`.

- **Data Modelling:**  
  Uses compound growth formulas and historical asset returns to simulate future portfolio values.

- **Visualization Layer:**  
  Powered by **Matplotlib** and **Plotly** for dynamic and clear visual outputs.

- **Frontend (Optional Web Integration):**  
  Built using HTML, CSS, and JavaScript for interactive user input and visualization display.

---

### 📈 Financial Logic Overview
FinWise evaluates multiple asset categories:
| Asset Class | Typical Return (p.a.) | Description |
|--------------|----------------------|--------------|
| Bonds | 6.5% | Low-risk, stable returns |
| Large-Cap Mutual Funds | 10.7% | Blue-chip equity exposure |
| Mid-Cap Mutual Funds | 11.25% | Balanced growth and risk |
| Small-Cap Mutual Funds | 11.85% | High-risk, high-reward assets |
| Gold | 9.3% | Inflation hedge and diversification |

The algorithm models these returns across 12 years (2020–2032) and aligns allocation with the investor’s expected growth rate.

---

### 🧭 Strategic Design Considerations
- **User-Centric Approach:** Focused on clarity, interactivity, and transparency.  
- **Scalable Architecture:** Easily expandable to include new asset classes or live financial data feeds.  
- **Integration Potential:** Can connect with APIs from investment platforms for real-time tracking.  
- **Educational Utility:** Designed for both investors and finance students to explore portfolio management concepts.

---

### 🧰 Use Cases
1. **Individual Investors:**  
   Discover personalized portfolio mixes suited to your financial goals.  
2. **Financial Advisors:**  
   Demonstrate data-backed recommendations to clients.  
3. **Institutions:**  
   Integrate the FinWise model as a module in larger financial planning systems.  

---

### 📈 Future Roadmap
- Incorporate **live market data** APIs for dynamic recalculations.  
- Introduce **Monte Carlo simulations** for probabilistic risk analysis.  
- Expand visualization with **interactive dashboards** using Streamlit or Dash.  
- Enable **automatic rebalancing suggestions** based on updated market trends.

---
