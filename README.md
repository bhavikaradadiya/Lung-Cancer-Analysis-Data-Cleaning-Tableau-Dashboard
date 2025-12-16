# Lung-Cancer-Analysis-Data-Cleaning-Tableau-Dashboard
This project analyzes  lung cancer dataset &amp; visualizes global health trends using Tableau. The dashboard highlights patterns such as diagnosis trends, demographic differences, treatment impact, and geographic distribution help clinicians, researchers, and public health policymakers in understanding lung cancer risk factors and survival outcomes.
## Dataset
Lung Cancer Analysis dataset is publically available.

 Dataset: https://www.kaggle.com/datasets/amankumar094/lung-cancer-dataset 

The Dataset named Lung_Cancer.csv having 890,000 records. its volume and granularity make it suitable for analytical and visualization purposes.
The dataset contains vivid aspects of lung cancer:
 age
 gender
 medical history
 lifestyle choices
 treatment outcomes.


---

## ✨ Key Features of the Project

### ✔ Data Cleaning & Feature Engineering
Performed in the **Google Colab notebook**:
- Converted date fields to proper `datetime` format
- Handled missing values using statistical methods
- Removed duplicate records
- Standardized categorical data (Gender, Smoking Status, Treatment Type)
- Created **calculated fields**:
  - `Age_Group`  
  - `Diagnosis_Year`  
  - `Treatment_Duration`  
- Exported a clean dataset ready for Tableau

---

## 📊 Tableau Dashboard Components

The dashboard includes the following visualizations:

### 🔹 1. Line Chart – Lung Cancer Cases Over Time  
Shows rising trends from 2015 to 2022, with decline after 2022 due to improved diagnosis and lifestyle changes.

### 🔹 2. Grouped Bar Chart – Survival by Stage & Gender  
Displays comparative survival outcomes for males vs females across cancer stages.

### 🔹 3. Geographic Map – Country-wise Case Distribution  
Reveals hotspots such as Ireland, France, Sweden, and Denmark.

### 🔹 4. Donut Chart – Distribution of Treatment Types  
Helps understand which treatment methods are most common.

### 🔹 5. Heatmap – Age Group vs Country  
Identifies that middle-aged groups show the highest number of cases.

---

## 🚀 How to Run the Project

### 1️⃣ Install Python Dependencies
Use the following command:

pip install -r requirements.txt

### 2️⃣ Run the Cleaning Notebook
Open:
notebooks/LungCancerDatasetCleaning.ipynb

This notebook performs:
- Loading the raw dataset  
- Executing all preprocessing steps  
- Saving the cleaned dataset to:

  /data/cleaned/Lung_Cancer_Cleaned.csv

  
### 3️⃣ Load the Dataset into Tableau
1. Open **Tableau Public / Desktop**
2. Connect to `Lung_Cancer_Cleaned.csv`
3. Create calculated fields in Tableau (if needed):
 - Age Group  
 - Diagnosis Year  
 - Treatment Duration  
4. Build or explore the dashboard using the prepared charts

### 4️⃣ View the Published Dashboard  
👉 Live Tableau Link:  
https://public.tableau.com/app/profile/bhavikaben.radadiya/viz/Lung_Cancer_Analysis_296/Story1
https://public.tableau.com/views/Lung_Cancer_Analysis_296/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 🛠 Technologies Used

| Component | Technology |
|----------|------------|
| Data Cleaning | Python (Pandas, NumPy), Google Colab |
| Visualization | Tableau Public |
| Supporting Tools | Matplotlib, Seaborn, Jupyter Notebook |

---

## 🔗 Reference Links

- 📘 Dataset: https://www.kaggle.com/datasets/amankumar094/lung-cancer-dataset  
- 🧹 Data Cleaning (Colab): *(from your project appendix)*  
- 📊 Tableau Dashboard: https://public.tableau.com/app/profile/bhavikaben.radadiya/viz/Lung_Cancer_Analysis_296/Story1  
- 🗂 GitHub Project Page: https://github.com/users/bhavikaradadiya/projects/2/settings  

---

## 👩‍💻 Author
**Bhavikaben Bavchandbhai Radadiya**  
*Visualization and Storytelling Using Tableau – 2025*

---

## 📄 License
This project is intended for academic and research purposes.  
User must ensure compliance with data privacy and ethical guidelines.










  
