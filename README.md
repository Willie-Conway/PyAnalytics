# 🐍 PyAnalytics — Interactive Python Data Analysis Platform

![alt text](Screenshots/PyAnalytics_Logo.png)

![PyAnalytics](https://img.shields.io/badge/PyAnalytics-Interactive_Python_Data_Analysis-6c63ff?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)

<p align="center">
  <img src="https://img.shields.io/badge/MODULES-6_COMPLETE-6c63ff?style=for-the-badge&labelColor=0b0c10" />
  <img src="https://img.shields.io/badge/INTERACTIVE_LESSONS-22-43e97b?style=for-the-badge&labelColor=0b0c10" />
  <img src="https://img.shields.io/badge/CHART_TYPES-15%2B-ff6584?style=for-the-badge&labelColor=0b0c10" />
  <img src="https://img.shields.io/badge/DATASETS-6-f9ca24?style=for-the-badge&labelColor=0b0c10" />
</p>

---

## Overview

PyAnalytics is an interactive web-based platform designed to teach Python data analysis through hands-on, visual learning. Built with HTML, CSS, JavaScript, and Chart.js, it provides an intuitive interface for exploring data wrangling, visualization, statistical testing, and machine learning concepts.

## ✨ Key Features

### 🎓 **6 Comprehensive Modules**

| Module                              | Focus                | Lessons    | Key Concepts                                            |
| ----------------------------------- | -------------------- | ---------- | ------------------------------------------------------- |
| **01 — Data Wrangling**      | Data Preparation     | 4 lessons  | Cleaning, Transformation, Missing Values, Normalization |
| **02 — EDA & Visualization** | Exploratory Analysis | 4 lessons  | Correlation, Distributions, Group Comparison, KDE       |
| **03 — Model Development**   | Machine Learning     | 4 lessons  | Linear Regression, Polynomial, Ridge, Evaluation        |
| **04 — Statistical Tests**   | Hypothesis Testing   | 4 lessons  | Chi-Square, T-Test, ANOVA, Pearson Correlation          |
| **05 — Practice Datasets**   | Real-World Data      | 6 datasets | Laptop, Insurance, Iris, Titanic, Housing, Sales        |
| **06 — Practice Arena**      | Knowledge Check      | 5 quizzes  | Concept Questions with Explanations                     |

---

## 📊 **Module 01: Data Wrangling**

### **4 Interactive Lessons** 🧹

| Lesson                   | Icon | Description                                       | Interactive Features                                               |
| ------------------------ | ---- | ------------------------------------------------- | ------------------------------------------------------------------ |
| **Data Cleaning**  | 🧼   | Clean dirty data with missing values and outliers | IQR outlier removal, median imputation, before/after visualization |
| **Transformation** | 🔄   | Apply mathematical transformations to data        | Log, sqrt, square, cube, exponential with live comparison          |
| **Missing Values** | ❓   | Handle missing data with various strategies       | Mean, median, interpolation, drop; visual comparison               |
| **Normalization**  | 📏   | Scale data for machine learning                   | Min-Max, Z-Score, Decimal Scaling with formula cards               |

### **Data Cleaning Simulator** ✨

- **Input dirty data** with placeholders (`NaN`, `?`, `null`)
- **Automatic outlier detection** using IQR method (1.5×IQR)
- **Median imputation** for missing values
- **Before/after visualization** with bar chart
- **Statistics displayed**: Original Mean, Cleaned Mean, Std Dev, Missing/Outlier count

### **Transformation Explorer** 🔢

- **5 transformations**: Log, Square Root, Square, Cube, Exponential
- **Real-time comparison** line chart
- **Formula cards** with mathematical equations
- **Log transformation** includes +1 to handle zeros

### **Missing Values Handler** ❓

- **4 strategies**: Mean, Median, Interpolation, Drop
- **Interactive method selection** with visual feedback
- **Line chart** showing original vs imputed data
- **Interpolation** estimates missing values from neighbors

### **Normalization Comparison** 📏

- **Min-Max scaling** → [0,1] range
- **Z-Score standardization** → mean=0, σ=1
- **Decimal scaling** → divide by power of 10
- **Overlay line chart** comparing all three methods

![alt text](<Screenshots/Data Wrangling.png>)

---

## 📈 **Module 02: EDA & Visualization**

### **4 Interactive Lessons** 📊

| Lesson                  | Icon | Description                             | Interactive Features                                   |
| ----------------------- | ---- | --------------------------------------- | ------------------------------------------------------ |
| **Correlation**   | 📈   | Explore relationships between variables | 3-variable scatter plots, correlation matrix, r values |
| **Distributions** | 📊   | Analyze data distributions              | Histogram, Density, Box Plot with statistics           |
| **Comparison**    | ⚖️ | Compare multiple groups                 | Group means vs standard deviations bar chart           |
| **KDE Plots**     | 🔍   | Kernel Density Estimation               | Actual vs predicted distribution overlay               |

### **Correlation Explorer** 📐

- **3 variables** input fields
- **Scatter plot matrix** showing relationships
- **Pearson correlation coefficients** displayed
- **Strength interpretation**: Very Strong (0.9+), Strong (0.7+), Moderate (0.5+), Weak (0.3+), Very Weak (<0.3)

### **Distribution Analyzer** 📊

- **Histogram** with automatic binning (8 bins)
- **Density plot** using Gaussian KDE
- **Box plot statistics**: Min, Q1, Median, Q3, Max
- **Summary statistics**: Mean, Median, Std Dev, IQR, Min, Max

### **Group Comparison** ⚖️

- **3 group inputs** (A, B, C)
- **Bar chart** showing means vs standard deviations
- **Quick visual comparison** of group differences

### **KDE Plot** 🔍

- **Actual vs Predicted** density comparison
- **Gaussian kernel** with Silverman's rule bandwidth
- **Overlay visualization** for model fit assessment

![alt text](<Screenshots/EDA & Visualization.png>)

---

## 🤖 **Module 03: Model Development**

### **4 Interactive Lessons** 📉

| Lesson                      | Icon | Description                       | Interactive Features                     |
| --------------------------- | ---- | --------------------------------- | ---------------------------------------- |
| **Linear Regression** | 📉   | Fit simple linear models          | Real-time slope/intercept, R², MSE      |
| **Polynomial**        | 📐   | Compare linear vs polynomial fits | Linear, quadratic, cubic comparison      |
| **Ridge Regression**  | 🏔️ | Regularization with L2 penalty    | Alpha slider, OLS vs Ridge comparison    |
| **Evaluation**        | 📊   | Regression metrics                | MSE, RMSE, MAE, R², error visualization |

### **Linear Regression** 📈

- **Input X and Y values** (comma-separated)
- **Calculates**: Intercept (β₀), Slope (β₁), R² Score, MSE
- **Scatter plot** with regression line overlay
- **Fit quality**: Excellent (R²≥0.9), Good (≥0.7), Moderate (≥0.5), Poor (<0.5)

### **Polynomial Regression** 📐

- **Compare linear, quadratic, and cubic fits**
- **Automatic coefficient estimation**
- **Overlay visualization** with different line styles
- **Demonstrates overfitting** with high-degree polynomials

### **Ridge Regression (L2 Regularization)** 🏔️

- **Alpha slider** (0.001–100) controls regularization strength
- **OLS vs Ridge** line comparison
- **Coefficient shrinkage** visualization
- **Cost function**: J(β) = Σ(yᵢ − ŷᵢ)² + αΣβⱼ²

### **Model Evaluation** 📊

- **Actual vs Predicted** input fields
- **Calculates**: MSE, RMSE, MAE, R²
- **Bar chart** showing actual, predicted, and error
- **Model quality rating** based on R²

![alt text](<Screenshots/Model Development.png>)

---

## 📊 **Module 04: Statistical Tests**

### **4 Interactive Lessons** 📈

| Lesson                    | Icon | Description             | Interactive Features                            |
| ------------------------- | ---- | ----------------------- | ----------------------------------------------- |
| **Chi-Square Test** | χ² | Test for independence   | 2×2 contingency table, p-value, interpretation |
| **T-Test**          | 📝   | Compare two group means | Independent t-test, p-value, significance       |
| **ANOVA**           | 📊   | Compare multiple groups | One-way ANOVA, F-statistic, p-value             |
| **Pearson r**       | 📐   | Correlation coefficient | r value, t-statistic, p-value, scatter plot     |

### **Chi-Square Test** χ²

- **2-row contingency table** input
- **Calculates**: χ² statistic, degrees of freedom, p-value
- **Interpretation**: "Significant" (p<0.05) or "Not Significant"
- **Formula card**: χ² = Σ((Oᵢ − Eᵢ)² / Eᵢ)

### **Independent T-Test** 📝

- **Two group inputs** (Group 1, Group 2)
- **Calculates**: Group means, t-statistic, p-value
- **Bar chart** showing means ± std dev
- **Interpretation**: "Significant" (p<0.05) or "Not Significant"

### **One-Way ANOVA** 📊

- **Three group inputs** (Group 1, 2, 3)
- **Calculates**: F-statistic, p-value, group means
- **Bar chart** with group mean comparison
- **Formula**: F = (SSB/dfb) / (SSW/dfw)

### **Pearson Correlation** 📐

- **X and Y variable inputs**
- **Calculates**: r value, strength, direction, t-statistic, p-value
- **Scatter plot** with regression line
- **Strength categories**: Very Strong, Strong, Moderate, Weak, Very Weak


![alt text](<Screenshots/Statistical Tests.png>)
---

## 📂 **Module 05: Practice Datasets**

### **6 Real-World Datasets** 📊

| Dataset                     | Icon | Features                               | Interactive Analysis                          |
| --------------------------- | ---- | -------------------------------------- | --------------------------------------------- |
| **Laptop Pricing**    | 💻   | RAM, Storage, CPU, Weight, Screen      | Scatter vs Price, Avg by Category, Trend Line |
| **Medical Insurance** | 🏥   | Smoker, Age, BMI, Region, Children     | Smoker comparison, Age groups, BMI categories |
| **Iris Dataset**      | 🌺   | Sepal Length/Width, Petal Length/Width | 3 species (Setosa, Versicolor, Virginica)     |
| **Titanic**           | 🚢   | Class, Gender, Age, Family Size        | Survival rates, age distribution              |
| **Housing Prices**    | 🏠   | Price, Rooms, Location, Size           | Price distribution, rooms vs price, location  |
| **Sales Data**        | 🛒   | Category, Monthly, Region              | Category breakdown, monthly trends            |

### **Dataset Features** ✨

- **Interactive dropdowns** for feature selection
- **Multiple chart types**: Scatter, Bar, Line, Box
- **Real-time updates** with data exploration
- **Summary statistics** for key variables

![alt text](<Screenshots/Practice Datasets.png>)

---

## 🎯 **Module 06: Practice Arena**

### **5 Knowledge Check Questions** 📝

| # | Question                                                                   | Topic                                                      |
| - | -------------------------------------------------------------------------- | ---------------------------------------------------------- |
| 1 | Which Python library is primarily used for data manipulation and analysis? | Pandas vs NumPy vs Matplotlib vs Scikit-learn              |
| 2 | What does the Chi-Square test determine?                                   | Association vs Mean Difference vs Correlation vs Normality |
| 3 | Ridge Regression adds which penalty term?                                  | L2 (sum of squared coefficients)                           |
| 4 | A p-value less than 0.05 typically indicates what?                         | Statistical significance                                   |
| 5 | Which metric is NOT appropriate for regression?                            | Accuracy (classification metric)                           |

### **Quiz Features** ✅

- **Multiple choice buttons** with letter indicators
- **Immediate feedback** with detailed explanations
- **Progress tracking** with animated bar
- **Score display** (X/5 correct)
- **Color-coded results**: Green for correct, Pink for incorrect

![alt text](<Screenshots/Practice Arena.png>)

---

## 🎨 **Design & Aesthetics**

### **Modern Data Science Interface** 🖥️

- **Dark background** (`#0b0c10`) — professional data science IDE aesthetic
- **Purple accent** (`#6c63ff`) for primary interactive elements
- **Green** (`#43e97b`) for EDA and success states
- **Pink** (`#ff6584`) for practice and warnings
- **Yellow** (`#f9ca24`) for statistical concepts
- **Blue** (`#4facfe`) for datasets

### **Typography** ✍️

- **Syne** — Bold headers, module titles, big numbers
- **JetBrains Mono** — Code blocks, formulas, technical labels
- **DM Sans** — Body text, descriptions, lesson content

### **Visual Elements** 🖼️

- **Noise overlay** for texture
- **Code blocks** with syntax highlighting
- **Formula cards** with mathematical equations
- **Stat cards** with values and descriptions
- **Progress bar** with smooth animation
- **Module color coding** for visual navigation

### **Module Color Scheme** 🎨

| Module              | Color  | Hex         | Usage                         |
| ------------------- | ------ | ----------- | ----------------------------- |
| **Wrangling** | Purple | `#6c63ff` | Data cleaning, transformation |
| **EDA**       | Green  | `#43e97b` | Visualization, distributions  |
| **Modeling**  | Orange | `#f7971e` | Regression, machine learning  |
| **Stats**     | Yellow | `#f9ca24` | Hypothesis testing            |
| **Datasets**  | Blue   | `#4facfe` | Real-world data               |
| **Practice**  | Pink   | `#ff6584` | Quiz, knowledge check         |

---

## 🛠️ **Technical Implementation**

### **Architecture**

```
┌─────────────────────────────────────┐
│        PyAnalytics Platform          │
├─────────────────────────────────────┤
│                                     │
│  ┌─────────────────────────────┐   │
│  │   Module Navigation          │   │
│  │   • 6 modules               │   │
│  │   • Color-coded tabs        │   │
│  │   • Active state tracking   │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │   Sidebar Lessons           │   │
│  │   • 4 lessons per module    │   │
│  │   • Lesson state persistence│   │
│  │   • Icon indicators         │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │   Interactive Calculators   │   │
│  │   • 20+ statistical fns    │   │
│  │   • Real-time updates      │   │
│  │   • Input validation       │   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │   Chart.js Integration      │   │
│  │   • 15+ chart types         │   │
│  │   • Dynamic data binding   │   │
│  │   • Destroy/recreate pattern│   │
│  └─────────────────────────────┘   │
│                                     │
│  ┌─────────────────────────────┐   │
│  │   Dataset Explorer          │   │
│  │   • 6 real-world datasets   │   │
│  │   • Feature selection       │   │
│  │   • Multiple chart types    │   │
│  └─────────────────────────────┘   │
└─────────────────────────────────────┘
```

### **Key Functions**

```javascript
// Statistical utilities
parseNums(s)                 // Parse comma-separated numbers
mean(arr), median(arr)       // Basic statistics
std(arr)                     // Standard deviation
pearsonR(x, y)               // Pearson correlation coefficient
kde(data, nPoints)           // Kernel Density Estimation
linReg(x, y)                 // Linear regression (intercept, slope, R²)

// Chart management
destroyChart(id)             // Clean up existing chart
makeChart(id, type, data, options) // Create new chart with options

// Module navigation
showModule(mod)              // Switch between main modules
showLesson(lesson)           // Switch lessons within module
showDataset(name, btn)       // Switch datasets in module 5

// Interactive calculators
cleanData()                  // Data cleaning simulator
updateTransformChart()       // Transformation explorer
handleMissingValues()        // Missing value imputation
updateNormChart()            // Normalization comparison
updateCorrelation()          // 3-variable correlation
calcRegression()             // Linear regression fit
calcChiSquare()              // Chi-square test
calcTTest()                  // Independent t-test
calcANOVA()                  // One-way ANOVA
calcPearson()                // Pearson correlation
```

---

## 📊 **Statistical Functions Implemented**

| Function                     | Formula                                            | Module      |
| ---------------------------- | -------------------------------------------------- | ----------- |
| **Mean**               | μ = Σx / n                                       | Stats, EDA  |
| **Median**             | middle value                                       | Stats, EDA  |
| **Standard Deviation** | σ = √[Σ(x-μ)² / n]                            | Stats, EDA  |
| **IQR**                | Q3 - Q1                                            | Wrangling   |
| **Pearson r**          | r = Σ((x-x̄)(y-ȳ)) / √[Σ(x-x̄)² Σ(y-ȳ)²] | Stats, EDA  |
| **Linear Regression**  | y = β₀ + β₁x                                   | Modeling    |
| **R² Score**          | 1 - (SSres / SStot)                                | Modeling    |
| **MSE**                | (1/n) Σ(yᵢ − ŷᵢ)²                            | Modeling    |
| **MAE**                | (1/n) Σ                                           | yᵢ − ŷᵢ |
| **Chi-Square**         | Σ((Oᵢ − Eᵢ)² / Eᵢ)                           | Stats       |
| **T-Statistic**        | t = (x̄₁ − x̄₂) / √(s₁²/n₁ + s₂²/n₂)   | Stats       |
| **F-Statistic**        | F = (SSB/dfb) / (SSW/dfw)                          | Stats       |
| **KDE**                | f̂(x) = (1/nh) Σ K((x − xᵢ)/h)                 | EDA         |

---

## 🎥 **Video Demo Script** (60-75 seconds)

| Time | Module    | Scene             | Action                                                                                |
| ---- | --------- | ----------------- | ------------------------------------------------------------------------------------- |
| 0:00 | Wrangling | Data Cleaning     | Input dirty data with NaN and 1000 outlier → Click Clean Data → Show cleaned values |
| 0:05 | Wrangling | Results           | Stats cards show Original Mean 148 → Cleaned Mean 65                                 |
| 0:10 | EDA       | Correlation       | Input 3 variables → Show scatter plot with r values 0.99, -0.99, -0.98               |
| 0:15 | Modeling  | Linear Regression | Input X/Y → Show regression line with R²=0.94                                       |
| 0:20 | Modeling  | Ridge             | Drag alpha slider from 1 to 50 → Ridge line shrinks toward horizontal                |
| 0:25 | Stats     | T-Test            | Group 1: 85-93, Group 2: 78-84 → Show p=0.0002 (Significant)                         |
| 0:30 | Stats     | ANOVA             | 3 groups with increasing means → Show F=14.2, p=0.0005                               |
| 0:35 | Datasets  | Laptop            | Select "RAM" and "Scatter" → Show gaming/ultrabook/notebook points                   |
| 0:40 | Datasets  | Insurance         | Select "Smoker" → Show $8.5k vs $32k bar chart                                       |
| 0:45 | Practice  | Quiz              | Answer Question 1 correctly → Progress bar updates to 1/5                            |
| 0:50 | Practice  | Feedback          | Show explanation with green success message                                           |

---

## 🚦 **Performance**

- **Load Time**: < 2 seconds (Chart.js CDN)
- **Memory Usage**: < 45 MB
- **CPU Usage**: Minimal (event-driven)
- **Network**: Chart.js only external dependency

---

## 🛡️ **Security Notes**

PyAnalytics is a **completely safe** educational platform:

- ✅ No data collection or tracking
- ✅ All calculations run in browser memory
- ✅ Chart.js from trusted CDN
- ✅ Pure HTML/CSS/JavaScript frontend
- ✅ Educational purposes only — learn data analysis concepts

---

## 📝 **License**

MIT License — see LICENSE file for details.

---

## **🙏🏿 Acknowledgments**

- **Pandas, NumPy, Scikit-learn** — Python data science ecosystem
- **Chart.js** — Beautiful, open-source charting library
- **IBM Data Science Curriculum** — Inspiration for learning progression
- **Kaggle** — Dataset inspiration (Iris, Titanic, Housing)
- **StatQuest with Josh Starmer** — Statistical concept clarity

---

## 📧 **Contact**

- **GitHub Issues**: [Create an issue](https://github.com/Willie-Conway/PyAnalytics/issues)
- **Website**: https://willie-conway.github.io/PyAnalytics/

---

## 🏁 **Future Enhancements**

- [ ] Add more datasets (20+ total)
- [ ] Include time series analysis
- [ ] Add classification models (logistic regression, SVM)
- [ ] Include clustering (K-Means, DBSCAN)
- [ ] Add ROC curves and confusion matrices
- [ ] Export analysis as PDF report
- [ ] Save user progress in localStorage
- [ ] Add challenge mode with timed quizzes
- [ ] Include real Python code generation
- [ ] Add model comparison dashboard

---

<p align="center">
  <strong>🐍 PyAnalytics — Learn Python Data Analysis Through Interactive Simulation 🐍</strong>
</p>

---

*Last updated: March 2025*
