# 🚗 Car Price Analysis

A comprehensive data analysis project exploring the relationship between car specifications and pricing using Python and advanced visualization techniques.

## 📊 Project Overview

This project analyzes car pricing data to identify key factors that influence vehicle prices. Through exploratory data analysis and correlation studies, we uncover insights into what drives car pricing in the automotive market.

## 🎯 Objectives

- **Data Cleaning**: Handle missing values and prepare dataset for analysis
- **Feature Engineering**: Create meaningful features and reduce redundancy
- **Correlation Analysis**: Identify strongest price predictors
- **Data Visualization**: Create interactive plots to showcase relationships
- **Business Insights**: Extract actionable insights for automotive industry

## 🛠️ Technologies Used

- **Python** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Plotly Express** - Interactive visualizations
- **Plotly Graph Objects** - Advanced plotting
- **Jupyter Notebook** - Development environment

## 📈 Key Findings

### Strong Price Correlations:
- **Horsepower**: 0.81 correlation - Performance drives premium pricing
- **Engine Size**: 0.87 correlation - Larger engines = higher prices
- **Curb Weight**: 0.84 correlation - Heavier cars cost more
- **City MPG**: -0.69 correlation - Fuel efficiency vs price trade-off

### Market Insights:
- Most cars priced between $5k-$15k (economy segment)
- Clear segmentation between budget and luxury vehicles
- Performance specifications are strongest price predictors

## 🔍 Data Processing Pipeline

1. **Data Loading & Inspection**
   - Loaded dataset with 26 features
   - Identified data types and structure

2. **Data Cleaning**
   - Checked null values (0% missing data)
   - Removed high-correlation columns
   - Handled categorical variables

3. **Feature Engineering**
   - Split CarName into CarCompany
   - Created car_stability feature
   - Applied dummy encoding for categorical variables

4. **Data Visualization**
   - Correlation heatmap analysis
   - Interactive scatter plots with color grading
   - Price distribution histograms

## 📸 Project Screenshots

### Correlation Heatmap
![Correlation Matrix](https://github.com/Harshvspr/Car_sales_analysis_python_project/blob/main/Screenshot%202025-06-25%20193830.png)
*Strong correlations between engine specs and price*

### Price vs Horsepower Analysis
![Price vs Horsepower](https://github.com/Harshvspr/Car_sales_analysis_python_project/blob/main/price%20vs%20horsepower.png)
*Clear positive relationship with color-coded pricing*

### Price vs Engine Size
![Price vs Engine Size](https://github.com/Harshvspr/Car_sales_analysis_python_project/blob/main/Screenshot%202025-06-25%20213240.png)
*Engine size as a key price predictor*

## 📁 Project Structure

```
car-price-analysis/
│
├── Car_Price_Analysis.ipynb    # Main analysis notebook
├── CarPrice_Assignment.csv     # Dataset
├── README.md                   # Project documentation
└── screenshots/               # Visualization images
    ├── correlation_heatmap.png
    ├── price_vs_horsepower.png
    └── price_vs_enginesize.png
```

## 🚀 Getting Started

### Running the Analysis
1. Clone the repository
```bash
git clone https://github.com/yourusername/car-price-analysis.git
cd car-price-analysis
```

2. Launch Jupyter Notebook
```bash
jupyter notebook Car_Price_Analysis.ipynb
```

3. Run all cells to reproduce the analysis

## 💡 Business Applications

- **Automotive Dealers**: Price estimation for inventory
- **Insurance Companies**: Risk assessment based on car specs
- **Manufacturers**: Market positioning and pricing strategy
- **Consumers**: Informed purchasing decisions

## 🔮 Future Enhancements

- [ ] Machine Learning price prediction models
- [ ] Advanced feature engineering
- [ ] Interactive dashboard deployment
- [ ] Market trend analysis over time
- [ ] Brand-specific pricing insights

## 📊 Dataset Information

- **Rows**: 205 car records
- **Features**: 26 original features (optimized to key predictors)
- **Target**: Car Price (USD)
- **Source**: Car sales dataset for predictive modeling

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Project Link: [https://github.com/Harshvspr/Car_sales_analysis_python_project](https://github.com/Harshvspr/Car_sales_analysis_python_project)

---

⭐ **Star this repo if you found it helpful!** ⭐
