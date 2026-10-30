# 🚗 Global Road Traffic Accident Analysis & Severity EDA

An in-depth Exploratory Data Analysis (EDA) investigating the patterns, causes, and impacts of road traffic accidents across multiple countries. This project explores how environmental factors, human behaviors, temporal patterns, and road infrastructure influence accident severity, casualties, and economic losses.

---

## 📌 Project Overview

Traffic accidents are among the leading causes of preventable injuries and economic loss worldwide. The objective of this project is to perform comprehensive exploratory data analysis on a multi-feature accident dataset to uncover hidden patterns, determine critical risk factors, and evaluate the relationships between driver behavior, weather conditions, road infrastructure, and accident outcomes.

---

## 📊 Dataset Highlights

The dataset (`accident.csv`) contains over 30 attributes structured across key dimensions:

* **Temporal Attributes:** Year, Month, Day of Week, Time of Day (Morning, Afternoon, Evening, Night).
* **Geographical & Spatial:** Country (USA, UK, Canada, India, China, Japan), Region, Population Density, Urban vs. Rural classification.
* **Environmental & Road Conditions:** Weather Conditions (Clear, Rainy, Foggy, Snowy, Windy), Visibility Level, Road Condition (Dry, Wet, Snow-covered, Icy), Road Type (Street, Highway, Main Road).
* **Driver & Vehicle Demographics:** Driver Age Group (18–25, 26–40, 41–60), Driver Gender, Driver Alcohol Level, Driver Fatigue status, Vehicle Condition.
* **Incident Characteristics & Causes:** Primary Accident Cause (Speeding, Distracted Driving, Weather, Mechanical Failure), Number of Vehicles Involved, Pedestrians and Cyclists Involved.
* **Impact & Severity Metrics:** Accident Severity (Minor, Moderate, Severe), Number of Injuries, Number of Fatalities, Emergency Response Time, Insurance Claims, Medical Cost, and Total Economic Loss.

---

## 🔍 Key Findings & Insights

1. **Multi-Factorial Dynamics:**
   * Correlation analysis reveals that numeric features (such as Speed Limit, Traffic Volume, Medical Costs, and Economic Loss) exhibit weak linear correlation with one another.
   * Accident occurrence and severity are primarily driven by **categorical and situational dynamics** (weather, road conditions, driver fatigue, and time of day) rather than isolated numerical variables.

2. **Temporal & Environmental Risks:**
   * Higher accident densities are observed during late afternoon and evening hours, coinciding with peak traffic transitions.
   * Adverse weather (rain, fog, snow) significantly escalates fatality rates, especially on high-speed road types such as highways.

3. **Human Behavior & Demographics:**
   * **Driver Fatigue** and **Distracted Driving** emerge as prominent contributing factors across multiple regions.
   * Younger driver demographics (18–25) and speeding behaviors show elevated involvement in severe accidents.

4. **Vulnerable Road Users:**
   * Pedestrian and cyclist involvement substantially increases the likelihood of severe injury and fatality in urban environments.

---

## 📈 Visualizations in the Notebook

* **Distribution Plots:** Temporal distributions (Year, Month, Day, Time of Day).
* **Comparative Bar Charts:** Total injuries and fatalities across road types and weather conditions grouped by country.
* **Box Plots & Histograms:** Distribution of medical costs and insurance claim volumes.
* **Correlation Heatmap:** Multi-feature numeric correlation matrix evaluating interdependencies.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`
* **Dataset:** `accident.csv`

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Zelarq/traffic-accident-analysis.git
cd traffic-accident-analysis
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Analysis
```bash
jupyter notebook accident_project.ipynb
```

---

## 👤 Author

* **Sayanth N K**
* GitHub: [@Zelarq](https://github.com/Zelarq)
* Email: [sayanthnk32@gmail.com](mailto:sayanthnk32@gmail.com)
