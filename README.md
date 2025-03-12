# 🏥 Hospital Data Analysis Project  

## 📌 Overview  
This project analyzes **hospital patient records** to uncover key insights into **hospital admissions, patient stay durations, medical procedures, and insurance coverage.** The analysis involved **data cleaning, feature engineering, and visualization** to support data-driven decision-making in healthcare management.  

---

## 📊 Dataset Details  
The project utilizes multiple datasets containing structured healthcare records:  

### 1️⃣ **Encounters Table**  
- Tracks **patient visits**, including **admission & discharge times**, **costs**, and **diagnosis codes**.  
- Key fields: `EncounterClass`, `Total_Claim_Cost`, `Payer_Coverage`, `ReasonCode`.  

### 2️⃣ **Patients Table**  
- Contains **demographic information** such as `BirthDate`, `Gender`, and `Marital Status`.  
- Added a new **"Alive" column** to analyze patient living status.  

### 3️⃣ **Procedures Table**  
- Records **medical procedures** with details on `Base_Cost`, `ReasonDescription`, and `Insurance Coverage`.  

### 4️⃣ **Organizations & Payers Tables**  
- **Organizations**: Includes hospital details like `Name`, `Location`, and `City`.  
- **Payers**: Contains **insurance provider details** and `Payer Coverage` data.  

---

## 🛠️ Data Processing & Analysis  
### 🔍 **Data Cleaning**  
✔ Filled missing values in **Reason Code** with a default value (0).  
✔ Dropped non-essential fields (`Prefix`, `First`, `Last`, `Suffix`, `Maiden`, `ZIP`).  
✔ Created a **new 'Alive' column** to distinguish living & deceased patients.  

### 📊 **Feature Engineering & Insights**  
✅ **Hospital Admissions Trend:** Analyzed the number of **admitted & readmitted** patients.  
✅ **Average Length of Stay:** **435.96 minutes per patient**.  
✅ **Average Cost Per Visit:** **$3,639**.  
✅ **Insurance Coverage Analysis:**  
   - ✅ **Covered Procedures:** `24,791`  
   - ❌ **Uncovered Procedures:** `22,910`  

### 📈 **Visualizations & Insights**  
- 📊 **Time-series trends** on **patient admissions**.  
- 📉 **Comparison of insured vs. uninsured procedures**.  
- 📍 **Geospatial distribution of hospitals & patient visits**.  

---

## 🚀 Key Takeaways  
🔹 **Data analytics can enhance hospital efficiency** by identifying patterns in admissions and costs.  
🔹 **Understanding insurance coverage gaps** helps optimize patient financial assistance programs.  
🔹 **Feature engineering on patient demographics** allows better patient outcome tracking.  

---

## 🏗️ Future Enhancements  
✅ Apply **predictive analytics** to forecast **hospital occupancy & patient admissions**.  
✅ Develop a **machine learning model** to predict **patient readmission risks**.  
✅ Expand **geospatial analysis** to assess hospital accessibility.  

---

## ⚡ Technologies Used  
- **Python**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`  
- **Jupyter Notebook**  
- **Data Visualization**  
