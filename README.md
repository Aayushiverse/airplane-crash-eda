# ✈️ Airplane Crash Data Analysis (1908–2023)
## 📚 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Conclusion](#conclusion)

## 🧭 Overview

This project analyzes over 5000 global airplane crashes from 1908 to 2023 to uncover patterns in fatality rates, regional risks, aircraft types, and more. It uses Python-based data analysis and visualization techniques to reveal trends and support better aviation safety understanding.


## 📊 Dataset

The dataset used for this analysis was sourced from [Kaggle: Airplane Crashes and Fatalities (up to 2023)](https://www.kaggle.com/datasets/nayansubedi1/airplane-crashes-and-fatalities-upto-2023), compiled by Nayan Subedi. It contains detailed records of airplane crashes from 1908 through 2023, covering over 5,000 incidents worldwide.

**Key features:**
- Date, location, and operator of each crash
- Aircraft type and route information
- Number of aboard, fatalities, and survivors
- Brief textual summary for each incident

**Enhancements made for analysis:**
- Extracted and engineered new features (e.g., year, era, location type, fatality ratio)
- Cleaned and normalized text fields for consistency
- Added categorical flags for summary keyword tagging and cause classification


## 📈 Key Insights

### 🧮 Fatality Insights
- Average of **31.2 people aboard** per crash; average of **22.4 fatalities**.
- **63.85%** of crashes were fully fatal (no survivors).
- **Tenerife disaster (1977)** is the deadliest with **583 deaths**.
- Crew deaths totaled ~17,000; passenger deaths exceeded **90,000**.
- Only **81 crashes (~1.6%)** recorded **zero fatalities**.

### 🛬 Aircraft & Operator Trends
- Older aircraft like **Douglas DC-3** appear most often in crash records.
- Post-2000, regional aircraft like **DHC-6 Twin Otter** and **Antonov AN-26** top crash frequency.
- High average fatalities in **Boeing 777**, **Airbus A300**, and **737 MAX 8**.
- **American Airlines**, **Indonesian Air Force**, and **Trigana Air** rank high in recent fatal crashes.

### 🌍 Location-Based Patterns
- **Russia**, **Indonesia**, and **Brazil** lead in crash counts since 2000.
- Crashes mostly occur **on land**, with water and mountain crashes less frequent.
- Cities like **Moscow**, **Tehran**, and **Goma** show high crash recurrence.

### 📆 Time-Based Trends
- Crash peaks during **WWII**, and civilian crashes peak in **1970s–80s**.
- Since 2000, both crash and fatality counts have **declined sharply**.
- Modern aviation is **safer**, with better survivability and fewer vague cause summaries.

### 🔤 Text Summary Analysis
- Frequent keywords: **engine**, **pilot**, **approach**, **runway**, **fire**, **collision**.
- Most cited causes: **fire**, **engine failure**, **storm**, **shot down**, and **explosions**.
- **94.7%** of crash summaries provide a **known cause**.
- Wartime summaries focus on enemy activity; modern ones highlight technical and operational failures.

---


## 🛠 Technologies Used

- Python (Pandas, NumPy)
- Data Visualization: Seaborn, Matplotlib
- NLP: WordCloud, Regex
- Jupyter Notebooks, VS Code

## 🧠 Skills Demonstrated

- Data Cleaning & Preprocessing
- Feature Engineering (date parsing, ratios, location normalization, etc.)
- Exploratory Data Analysis (EDA) using Seaborn, Matplotlib, Pandas
- Text Mining & Keyword Analysis
- Time Series & Era-Based Comparisons
- Data Storytelling & Visual Communication

## ✅ Results

The project identifies both human and machine factors in aviation safety. It reveals that most crashes are caused by operational issues, with high-risk zones in developing airspaces. The analysis also captures the evolution of aviation language and incident reporting across wartime and modern eras.


## 🧠 Conclusion

This project demonstrates the power of combining statistical analysis with text mining to understand aviation incidents. It helped uncover patterns, recognize reporting improvements, and reinforced the importance of data-driven safety practices.

## 📎 License

This project is for educational and portfolio purposes. Dataset belongs to original author [Nayan Subedi](https://www.kaggle.com/datasets/nayansubedi1/airplane-crashes-and-fatalities-upto-2023).
