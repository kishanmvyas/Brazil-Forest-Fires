# Brazil Forest Fires Analysis 🌲🔥

A data-driven exploration of forest fire trends in Brazil between 1998 and 2017, highlighting regional patterns and seasonal variation.

---

## 📊 Project Summary

* Analyzes a Brazilian forest fires dataset, detailing annual and monthly fire counts per state ([github.com][1]).
* Aims:

  * Visualize fire hotspot trends over time.
  * Identify high-risk regions and seasonal patterns.
  * Examine correlations with environmental factors.

---

## 📁 Dataset

From the publicly available “Forest Fires in Brazil” dataset:

* Covers **1998–2017**.
* Contains **year**, **month**, **state**, and **number of fires** per state ([greenpeace.org][2], [kaggle.com][3]).

---

## 🛠 Tech Stack

* **Python 3** in a Jupyter Notebook (`BrazilForest.ipynb`)
* **Pandas**, **NumPy** – data wrangling
* **Matplotlib**, **Seaborn** – static visualizations
* **Plotly** (optional) – interactive charts for deeper insight

---

## 🔍 Workflow Outline

1. **Data Ingestion** – Load and clean CSV data.
2. **Exploratory Data Analysis (EDA)**

   * Annual fire trends
   * State-level comparisons
   * Seasonal (month) variation
3. **Visualization**

   * Time series plots
   * Choropleth/state heatmaps
   * Multi-year seasonal trend analysis
   * Optionally, interactive Plotly visuals
4. **Insights**

   * Analyze which states are most affected
   * Determine peak fire months
   * Detect long-term patterns

---

## 📈 Key Findings *(example to update after your run)*

* States like **Amazonas**, **Mato Grosso**, and **Pará** consistently experience the highest fire counts.
* Fire activity peaks in **dry season months** (e.g. August–October).
* Overall, there's been an **upward trend** in annual fire hotspots in certain regions over two decades.

---

## 🚀 Enhancements

* Embed **Plotly** for interactive maps/charts.
* Use **choropleth** for state-level intensity.
* Integrate **external datasets** (e.g. rainfall, land-cover, deforestation rates).
* Expand temporal coverage beyond 2017 with updated satellite/INPE data.
* Apply **time-series forecasting** (e.g. ARIMA) to model future fire patterns.

---

## 📂 Repository Structure

```
/
├─ BrazilForest.ipynb       # Main analysis notebook
├─ data/                    # Raw CSV dataset
├─ figures/                 # Exported plots/images
└─ README.md                # Project documentation
```

---

## 🔧 Requirements

* Python ≥ 3.7
* pandas, numpy, matplotlib, seaborn
* plotly (optional—install via `pip install plotly`)

---

## 🛠 How to Run

1. Clone or download this repo:

   ```bash
   git clone https://github.com/kishanmvyas/Brazil-Forest-Fires.git
   cd Brazil-Forest-Fires
   ```
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Launch the notebook:

   ```bash
   jupyter notebook BrazilForest.ipynb
   ```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for:

* Data enhancements (e.g. adding newer years)
* Richer visualizations (Plotly dashboards, map layers)
* Statistical or machine learning analysis
* Deployment (e.g. web app)

---

## 📜 License

MIT License – see [LICENSE](./LICENSE) for details.

---

## 👤 Author

**Kishan Vyas**
📬 [kishanvyas.m@gmail.com](mailto:kishanvyas.m@gmail.com)

