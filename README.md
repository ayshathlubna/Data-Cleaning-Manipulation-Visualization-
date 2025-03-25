# **Airbnb NYC Data Analysis: Data Cleaning, Manipulation & Visualization** 🏡📊  

## **📌 Overview**  
This project applies **data cleaning, exploratory data analysis (EDA), feature engineering, and visualization techniques** to real-world Airbnb NYC data. It is designed to demonstrate practical applications of the concepts covered in my previous posts.  

💡 **Key areas covered in this project:**  
✔ Handling **missing values** using various imputation techniques (Mean, Median, Mode, KNN)  
✔ Identifying and **removing duplicates** to ensure data integrity  
✔ **Feature engineering & selection** for better data representation  
✔ **Outlier detection & handling** using IQR method  
✔ **Data visualization** using Seaborn, Matplotlib, and interactive Folium maps  
✔ **Geospatial analysis** to identify price variations across different neighborhoods  

🔗 **Check out the LinkedIn posts that explain these concepts in detail:**  
- Handling Missing Values: [Insert Link]  
- Removing Duplicates: [Insert Link]  

---

## **📂 Dataset**  
We use the **AB_NYC_2019.csv** dataset, which contains information on Airbnb listings across New York City.  

### **🔹 Features in the dataset:**  
- **Categorical Features:** Room type, neighborhood, host information  
- **Numerical Features:** Price, number of reviews, availability  
- **Geospatial Data:** Latitude, longitude  

---

## **🛠 Steps in the Project**  

### **1️⃣ Data Cleaning & Preprocessing**  
- Dropped unnecessary columns (**id, host_name, last_review**)  
- Handled **missing values** in `reviews_per_month` using KNN imputation  
- Replaced missing names with `"Not Available"`  
- Checked and confirmed **no duplicate records**  

---

### **2️⃣ Handling Outliers & Skewed Data**  
- Used **IQR (Interquartile Range) method** to detect extreme price values  
- Applied **log transformation** to normalize skewed features  

---

### **3️⃣ Exploratory Data Analysis (EDA) & Visualizations**  
📊 **Visualizing data distributions & trends:**  
- **Price Analysis** – Histograms & boxplots for price distribution  
- **Neighborhood Insights** – Bar charts for room type & price variations across boroughs  
- **Top Hosts & Listings** – Pie charts for the most active Airbnb hosts  
- **Geospatial Visualizations** – Heatmaps & scatterplots for listing density  

📍 **Interactive Mapping with Folium:**  
- **Heatmaps** – Show high-density Airbnb areas in NYC  
- **Clustered Maps** – Grouping listings to identify price variations by location  

---

### **4️⃣ Feature Engineering & Selection**  
✔ Created **new features** (`price_per_night`, `price_category`)  
✔ Transformed skewed features using **log transformation**  
✔ Scaled numerical features using **Standardization & MinMax Scaling**  
✔ Encoded categorical data using **Label Encoding & One-Hot Encoding**  
✔ Selected the best features based on **correlation analysis**  



## **📺 Watch the Project in Action!**  
🎥 **I’ve attached a screen recording of the project walkthrough so you can see how everything comes together!**  

---

## **📂 How to Run the Project**  
### **🔧 Requirements**  
Ensure you have the following libraries installed:  

```python
pip install numpy pandas seaborn matplotlib scikit-learn folium
```

### **▶ Running the Project**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/Airbnb-NYC-Data-Analysis.git
   ```
2. Navigate to the directory:  
   ```bash
   cd Airbnb-NYC-Data-Analysis
   ```
3. Run the Jupyter Notebook or Python script to execute the analysis.  

---

## **📜 Summary & Insights**  
🏡 **Manhattan & Brooklyn** have the highest average listing prices.  
🔥 **Entire apartments** are the most expensive, while **shared rooms** are the cheapest.  
📍 **Williamsburg, Bedford-Stuyvesant, and Harlem** have the highest Airbnb listings.  
💰 **Some listings exceed $10,000/night** – indicating luxury stays or possible data entry errors.  

---

## **📥 Download the Full Project**  
📂 **[Click here to access the full project](GitHub Repo Link)**  

---

## **📢 Let’s Connect!**  
If you found this project helpful, let's discuss! Feel free to reach out on **LinkedIn** or drop a comment below. 🚀  

#DataScience #Python #DataCleaning #EDA #DataVisualization #FeatureEngineering #MachineLearning  
