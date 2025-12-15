# Global Emission Trends Analysis (2000–2020)

## 📌 Project Overview
Monitoring greenhouse gas emissions is essential for understanding climate change and developing effective mitigation strategies. This project analyzes historical global emission data from 2000 to 2020 to uncover long-term trends, identify major contributors, study sector-wise impacts, and build predictive models for future emission levels.

---

## 🎯 Project Goals
- Analyze historical global greenhouse gas emission patterns  
- Identify top emitting countries, regions, and sectors  
- Understand how emissions have evolved over time (2000–2020)  
- Compare emissions across regions and economic groups  
- Build and evaluate predictive models for future emission forecasting  

---

## 📊 Dataset Description
The project uses the dataset **“Total Emissions Per Country (2000–2020).csv”**, which provides a comprehensive global view of emissions over two decades.

### Dataset Structure
- **Areas:** Individual countries (e.g., Afghanistan, Albania) and grouped regions (OECD, Asia, Non-Annex I countries)  
- **Items:** Emission sources such as Crop Residues, Enteric Fermentation, LULUCF, Synthetic Fertilizers  
- **Elements:** Emission types including CO₂, N₂O, and CO₂-equivalent (AR5)  
- **Timeline:** Annual data from 2000 to 2020  

This structure enables both granular and aggregated analysis across geography, sector, and time.

---

## 🔄 Data Science Workflow
The project follows a structured data science pipeline:

1. **Business Understanding** – Define objectives: analyze trends and predict future emissions  
2. **Data Collection** – Load and inspect the emissions dataset  
3. **Data Preparation** – Clean, filter, and aggregate data for analysis  
4. **Exploratory Data Analysis (EDA)** – Visualize trends, distributions, and top contributors  
5. **Modeling** – Train regression models for emission prediction  
6. **Model Evaluation** – Compare model performance to select the most effective approach  

---

## 📈 Exploratory Data Analysis (EDA) Highlights

### Top Emitters
Analysis of CO₂-equivalent emissions highlights that global emissions are heavily concentrated in a small number of countries and regions, indicating key targets for climate intervention.

### Global Emission Trends (2000–2020)
- Overall global emissions have steadily increased over the two decades  
- Regions such as Asia and Non-Annex I countries show strong upward trends  
- OECD and Americas exhibit relatively stable emission patterns  

### 2019 vs 2020 Emissions
A comparative analysis reveals noticeable shifts in emission levels across regions, offering insights into short-term global changes and disruptions.

---

## 🤖 Predictive Modeling
To move beyond descriptive analysis, machine learning models were developed to forecast future emissions based on historical data.

### Models Implemented
- Linear Regression (baseline)  
- Random Forest Regressor  
- LightGBM (LGBM)  
- CatBoost  

### Key Modeling Insights
- Advanced models such as **Random Forest, LGBM, and CatBoost** significantly outperform simple linear models  
- These models effectively capture complex, non-linear emission trends  
- Predictive modeling transforms historical data into an **early-warning system** for policy and strategic planning  

---

## 🌐 Interactive Prediction Tool
The project includes a predictive application that allows users to manually input emission-related variables and receive **real-time emission forecasts** using trained LGBM/CatBoost models. This demonstrates how data science insights can be operationalized into practical tools.

---

## 🧠 Key Takeaways
- Global emissions are highly concentrated among a few countries and regions  
- Long-term trends show a consistent rise in global emissions  
- Machine learning models provide strong predictive power for environmental data  
- Combining EDA with ML offers a robust framework for both understanding past behavior and forecasting future trends  
- Data-driven insights can support smarter environmental policy and planning  

---

## 🛠️ Tools & Technologies
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Models:** Random Forest, LightGBM, CatBoost  
- **Visualization:** Line plots, bar charts, comparative scatter plots  

---

## 👩‍💻 Team Members
Jahnavi 
Subhasree Yenigalla


---

