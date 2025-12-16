# 🏠 Airbnb Market Dynamics in Paris

![Airbnb view paris](https://www.parisperfect.com/cdn-cgi/image/format=auto,width=1256/https://www.parisperfect.com/g/photos/upload/best-airbnb-paris.jpg)


## 📖 Project Description

This project presents a detailed exploratory data analysis of the Airbnb market in Paris, examining how regulatory interventions, spatial locality differences, and pricing mechanisms have influenced market behavior over time.

The study focuses on understanding changes in host participation, listing growth, and average nightly prices, using historical Airbnb data. Through systematic data cleaning and visualization-driven analysis, the project derives meaningful insights and practical recommendations for stakeholders in the short-term rental ecosystem.


---

## 🎯 Objectives

- Examine Airbnb listing growth trends in Paris from 2008 onwards
- Assess the impact of the 2017 Paris short-term rental regulations
- Analyze price variation across neighborhoods
- Study the relationship between guest capacity and nightly prices
- Identify temporal trends in pricing and host entry
- Generate business-oriented insights and recommendations


---

## 📊 Key Findings

- Early Expansion (2008–2016): Airbnb experienced rapid growth in Paris, with peak host entry during 2015–2016.
- Regulatory Impact (Post-2017): The introduction of rental regulations led to a sharp decline in new host registrations.
- Supply–Demand Imbalance: Despite slower supply growth, traveler demand remained relatively stable.
- Pricing Evolution:
  - Early Market Phase (2008–2009): Prices were high due to limited supply and early market scarcity.
  - Competitive Phase (2010–2014): Increased host entry intensified competition, leading to a decline in average prices.
  - Stabilization Phase (2015–2017): Prices stabilized as supply and demand reached relative equilibrium.
  - Post-Regulation Phase (2018–2020): Supply constraints following regulations contributed to rising prices.
  - Pandemic Impact (2021 onwards): Travel disruptions led to a temporary decline in average prices.
- Spatial Price Differences: Central and prestigious districts command premium prices, while outer neighborhoods remain more affordable.
- Capacity Effect: Larger accommodations charge significantly higher nightly rates, though the relationship is not strictly linear.


---

## 🚀 Business Implications & Recommendations

- Prioritize high-demand central localities while maintaining budget-friendly options in outer districts.
- Apply data-driven dynamic pricing strategies based on seasonality, location, and capacity.
- Promote medium-capacity listings (3–6 guests) for optimal balance between demand and profitability.
- Enhance customer experience through quality standards, verified listings, and flexible amenities.
- Maintain regulatory compliance and adapt operational strategies to evolving housing policies.


---

## 🛠️ Tools & Technologies

- Python:
  - pandas
  - numpy

- Data Visualization:
  - Matplotlib
  - Seaborn

- Jupyter Notebook for interactive analysis


---

## 📂 Project Structure

```
├── data/                  # Raw & cleaned datasets
├── notebooks/             # Jupyter notebooks
├── images/                # Visualizations exported from notebooks
├── requirements.txt       # Python Dependencies
├── LICENSE                # License file (MIT)
├── README.md              # Project overview (this file)
```

---

## ⚙️ How to Run the Project

1. Clone the repository
```
git clone https://github.com/your-username/airbnb-paris-analysis.git
cd airbnb-paris-analysis
```

2. Install required libraries
 ```
pip install -r requirements.txt
```

3. Launch Jupyter Notebook
```
jupyter notebook
```

4. Open the notebook and execute cells sequentially.


---

## 📈 Output & Visualizations

The notebook includes visualizations such as:

- Airbnb listing growth over time
  <img width="1547" height="813" alt="listings_growth" src="https://github.com/user-attachments/assets/5257f33c-91d8-49ac-8fa5-354b7a545f4d" />

- Average nightly prices by locality
<img width="1546" height="853" alt="price_locality" src="https://github.com/user-attachments/assets/5bc9168a-4450-41f9-88dd-9ac584d5870c" />

- Impact of the 2017 regulation on host entry
<img width="1528" height="932" alt="regulation_impact" src="https://github.com/user-attachments/assets/c720e80d-34d0-4f86-8a15-db1ae005064e" />

- Price variation by accommodation capacity
<img width="1183" height="781" alt="Accomodation price" src="https://github.com/user-attachments/assets/7fa9dd1c-2497-4b09-a0f0-bd0ebbc25de9" />

(All figures are generated directly within the notebook.)


---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for more information.


---

## 🙏 Acknowledgments

- **[Inside Airbnb](http://insideairbnb.com/)** for providing the dataset.
- Public information on **Paris housing and short-term rental regulations**.


---

## 🔮 Future Enhancements

- Extend the analysis to **other global cities** for comparative insights.
- Apply **time-series or regression models** for price prediction.
- Develop an **interactive dashboard** using **Plotly or Power BI**.


---

## ✅ Final Note

This project demonstrates how **data analysis can be used to understand the interaction between regulation, market behavior, and pricing strategies**. Paris serves as a compelling case study of how policy decisions reshape urban short-term rental markets.

---
