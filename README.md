# 🌱 UAV Potato Disease Monitoring Dashboard

> **Interactive UAV Potato Disease Dataset Analytics using Python & Tableau**  
> Developed during a **Data Analytics Internship at IIT Jammu**

---

## 📌 Project Overview

The **UAV Potato Disease Monitoring Dashboard** is an end-to-end data analytics project focused on exploring and understanding a UAV-based potato disease detection dataset.

Instead of building a machine learning model, this project emphasizes **data preprocessing, feature engineering, exploratory data analysis (EDA), and interactive dashboard development** to uncover meaningful insights from agricultural imagery annotations.

Using **Python** for preprocessing and **Tableau** for visualization, the project transforms raw annotation data into an interactive analytical dashboard that enables users to explore disease distributions, spatial characteristics, and engineered features.

---

## 🎯 Objectives

- Analyze UAV potato disease annotation data
- Perform data cleaning and preprocessing
- Engineer meaningful geometric and spatial features
- Conduct exploratory data analysis (EDA)
- Build interactive Tableau dashboards
- Generate actionable insights for agricultural monitoring
- Present findings through an intuitive visual interface

---

## 🔄 Project Workflow

```text
UAV Annotation Dataset
          │
          ▼
Data Cleaning & Preprocessing
          │
          ▼
Feature Engineering
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Insight Generation
          │
          ▼
Interactive Tableau Dashboard
```

---

## 📂 Dataset Information

| Attribute | Details |
|------------|---------|
| Dataset Type | UAV Potato Disease Detection Dataset |
| Total Annotations | **7,506** |
| Disease Classes | **3** |
| Classes | Potato Early Blight, Potato Late Blight, Healthy Plant |
| Dataset Split | Train, Validation, Test |

---

## ⚙️ Feature Engineering

The following analytical features were engineered from the annotation dataset:

- Bounding Box Area
- Bounding Box Perimeter
- Bounding Box Diagonal
- Aspect Ratio
- Area-to-Perimeter Ratio
- X Center
- Y Center
- Width
- Height
- Center Distance

These engineered features enabled deeper spatial and geometric analysis of disease annotations beyond the original dataset.

---

## 📊 Exploratory Data Analysis

The project investigates several important characteristics of the dataset, including:

- Disease Class Distribution
- Dataset Split Distribution
- Bounding Box Area Distribution
- Aspect Ratio Analysis
- Detection Size Distribution
- Spatial Occupancy Analysis
- Feature Correlation
- Center Distance Analysis
- Spatial Zone Analysis
- Geometric Feature Comparisons

---

# 📈 Interactive Tableau Dashboard

The project consists of three interactive analytical dashboards.

---

## 🔹 Overview Dashboard

Provides a comprehensive summary of the dataset through:

- KPI Cards
- Disease Class Distribution
- Dataset Split Analysis
- Bounding Box Area Distribution
- Dataset Statistics

### Screenshot

![Overview Dashboard](Dashboard%20Images/Overview.png)

---

## 🔹 Disease Analysis Dashboard

Focuses on disease-wise analytical comparisons by exploring:

- Engineered Feature Comparisons
- Disease-wise Detection Characteristics
- Distribution Analysis
- Feature Relationships
- Statistical Comparisons

### Screenshot

![Disease Analysis Dashboard](Dashboard%20Images/Disease%20Analysis.png)

---

## 🔹 Spatial Analysis Dashboard

Explores the spatial behaviour of disease detections including:

- Detection Position Analysis
- Spatial Zone Distribution
- Center Coordinate Analysis
- Spatial Occupancy Patterns
- UAV Annotation Characteristics

### Screenshot

![Spatial Analysis Dashboard](Dashboard%20Images/Spatial%20Analysis.png)

---

# 🌐 Live Interactive Dashboard

Explore the fully interactive Tableau Dashboard here:

### 🔗 Tableau Public

**https://public.tableau.com/app/profile/soham.sharma8884/viz/UAVPotatoDiseaseMonitoringDashboard/Dashboard1?publish=yes**

---

## 💡 Key Insights

- The dataset contains **7,506 annotated disease instances** across three potato disease classes.
- Early Blight represents the largest proportion of disease annotations.
- Most detections exhibit relatively high aspect ratios.
- Training data forms the majority of the dataset split.
- Bounding box characteristics reveal meaningful differences between disease categories.
- Spatial analysis identifies distinct detection concentration patterns.
- Feature engineering significantly improves analytical understanding of the dataset.

---

## 🛠️ Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Visualization

- Tableau Public

### Development Environment

- Jupyter Notebook

---

## 📁 Repository Structure

```text
UAV-Potato-Disease-Monitoring-Dashboard
│
├── Dashboard Images
│   ├── Overview.png
│   ├── Disease Analysis.png
│   └── Spatial Analysis.png
│
├── Dataset
│
├── notebooks
│
├── tableau
│   └── UAV Potato Disease Monitoring Dashboard.twbx
│
├── README.md
└── LICENSE
```

---

## 🚀 Future Improvements

- Advanced spatial analytics
- Additional agricultural datasets
- Temporal disease progression analysis
- GIS integration
- Predictive machine learning integration
- Automated insight generation
- Real-time UAV monitoring dashboards

---

## 👨‍💻 Author

**Soham Sharma**

Data Analytics | Python | SQL | Tableau | Power BI

---

⭐ If you found this project interesting, consider giving the repository a star.
