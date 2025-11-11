# Play Store Analytics 

### **Project Title:** 
Play Store Analytics: Trends, Ratings & Installs



---

##  **Project Overview**

This project involves an in-depth analysis of the **Google Play Store dataset** to uncover trends, performance patterns, and key insights about mobile applications.  
The analysis aims to help understand which categories dominate, how app ratings correlate with installs, and the ratio of free vs paid apps.  

After performing **Exploratory Data Analysis (EDA)** and cleaning the dataset, an interactive **Power BI dashboard** was created to visually represent the insights.

---

##  **Objectives**

- Identify **top-performing app categories** based on installs.  
- Compare **average ratings across content ratings** (age suitability).  
- Understand the **distribution of free vs paid apps**.  
- Find the **number of 5-star rated apps**.  
- Explore the **correlation between installs and ratings**.  
- Present findings in an interactive, visually appealing Power BI dashboard.

---
##  **Dashboard Preview:**

![Play Store Analytics Dashboard](https://raw.githubusercontent.com/Groverbhumi/Googleplaystore-analysis/main/Playstore_dashboard.png)

---

## ⚙️ **Data Cleaning & EDA Summary**

### **Steps Performed:**
1. **Removed missing and duplicate values** to ensure data quality.  
2. **Handled inconsistent data formats** (e.g., installs, price, size).  
3. **Converted installs and reviews to numeric format** for aggregation.  
4. **Cleaned columns like `Size`, `Current Ver`, and `Android Ver`**.  
5. **Extracted Date parts** (`Day`, `Month`, `Year`) from `Last Updated`.  
6. **Standardized categories** to ensure uniform grouping.  
7. **Derived new metrics** for visualization (e.g., total installs, avg rating).

### **Dataset Columns Used**
| Column Name | Description |
|--------------|-------------|
| App | App Name |
| Category | App Category |
| Rating | User Rating |
| Reviews | Number of Reviews |
| Size | App Size |
| Installs | Total Number of Installs |
| Type | Free / Paid |
| Price | App Price |
| Content Rating | Target Age Group |
| Genres | App Genre |
| Last Updated | Date of Last Update |
| Current Ver | Current App Version |
| Android Ver | Minimum Android Version Required |

---

## 📊 **Power BI Dashboard Overview**

### **Key Metrics (KPIs):**
- **Total Apps:** 9,638  
- **Total Installs:** 167.63K  
- **Average Rating:** 4.19  
- **5 Rating Apps:** 274  

---

### **Dashboard Sections & Visuals**

| Section | Visualization | Description |
|----------|----------------|--------------|
| **Top KPIs** | Card visuals | Summarize key app metrics (total apps, installs, avg rating, 5★ apps) |
| **Top Categories by Installs** | Bar chart | Displays the 5 most-installed app categories |
| **Avg Rating by Content Rating** | Column chart | Compares ratings across different audience age groups |
| **App Distribution (Free vs Paid)** | Donut chart | Shows percentage of free vs paid apps |
| **Category Breakdown (Free/Paid)** | Matrix table | Displays number of free and paid apps by category |
| **Rating vs Install** | Scatter plot | Illustrates correlation between ratings and installs |
| **Category Filter** | Dropdown slicer | Allows filtering all visuals by app category |

---

## **Key Insights**

-  **Top Categories:** Games and Communication dominate installs.  
-  **Monetization:** 92% of apps are **Free**, while 8% are **Paid**.  
-  **Average Ratings:** Most apps are rated between **4.0 and 4.5** across age categories.  
-  **5-Star Apps:** There are 274 apps with perfect ratings.  
-  **Correlation:** Higher installs generally align with higher ratings in entertainment-focused categories.  
-  **Category Mix:** Tools, Productivity, and Shopping show a strong presence of both free and paid apps.

---



##  **Tools & Technologies**

| Tool | Purpose |
|------|----------|
| **Power BI** | Data Visualization |
| **Excel / Python** | Data Cleaning and Preprocessing |
| **Google Play Store Dataset** | Source Dataset |

---
## © 2025 **Bhumika Grover**


