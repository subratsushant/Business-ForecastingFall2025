# FAO Food Price Index (Monthly) 

This repository contains the required files for the Forecasting Models.  
The dataset chosen is the **FAO Food Price Index (FFPI)**, which provides a monthly measure of international food commodity prices.

---

## 1. Data File 
- File: **FoodPriceIndex.csv**
- Source: Food and Agriculture Organization (FAO) of the United Nations  
- Download link: [FAO Food Price Index CSV](https://www.fao.org/fileadmin/templates/worldfoodsituation/downloads/FoodPriceIndex/FoodPriceIndex.csv)  
- Coverage: January 1990 – present  
- Frequency: Monthly  

---

## 2. Data Dictionary 

| Field Name               | Type   | Units / Format         | Description |
|--------------------------|--------|------------------------|-------------|
| Date                     | Date   | YYYY-MM                | Month and year of the observation |
| Food Price Index         | Float  | Index (2014–2016=100)  | Composite FAO Food Price Index measuring the average price change of a basket of food commodities |
| Cereals Price Index      | Float  | Index (2014–2016=100)  | Index covering wheat, maize, rice, and barley prices |
| Dairy Price Index        | Float  | Index (2014–2016=100)  | Index based on world prices of butter, cheese, skim milk powder, and whole milk powder |
| Meat Price Index         | Float  | Index (2014–2016=100)  | Index covering bovine, ovine, pig, and poultry meat prices |
| Sugar Price Index        | Float  | Index (2014–2016=100)  | Index based on international sugar price quotations |
| Vegetable Oils Price Index | Float | Index (2014–2016=100) | Index tracking prices of major edible oils (palm, soy, rapeseed, sunflower) |

---

## 3. Data Collection Methodology 
- **Collector:** Food and Agriculture Organization (FAO) of the United Nations  
- **Source:** International commodity price quotations from trade statistics, commodity exchanges, and official reports  
- **Base Period:** 2014–2016 = 100  
- **Frequency:** Monthly, published around the first week of each month  
- **Sub-indices:** Cereals, Dairy, Meat, Sugar, Vegetable Oils  
- **Notes:** Composite index is a weighted average of the sub-indices. FAO revises data when improved price information becomes available.

---

## 4. Why this dataset intrigues me 
Food prices are critical indicators of global food security, economic stability, and inflation. The FAO Food Price Index captures both **short-term volatility** (e.g., weather shocks, energy costs, conflicts) and **long-term structural changes** (climate change, agricultural policies, trade patterns).  
With over 30 years of monthly data, this dataset is perfect for applying and comparing different time series forecasting models. Forecasting it can support policymaking, business strategy, and humanitarian planning.

---

