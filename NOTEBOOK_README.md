# Manufacturing AI Pre-Test: Energy Consumption Analysis

## Overview
This Jupyter Notebook contains a comprehensive analysis of energy consumption in pharmaceutical drying systems. It demonstrates data science best practices for manufacturing optimization.

## Contents

### 📊 Sections
1. **Section A: Data Understanding**
   - Dataset exploration and statistics
   - Missing values and outlier analysis
   - Distribution and correlation analysis
   - Target variable selection with justification

2. **Section B: Predictive Modeling**
   - Feature engineering
   - Multiple model comparison (Linear Regression, Random Forest, Gradient Boosting)
   - Model justification and parameter tuning

3. **Section C: Evaluation & Interpretation**
   - Performance metrics (MAE, RMSE, R²)
   - Visualization (Actual vs Predicted, Residuals)
   - Feature importance analysis
   - Manufacturing context interpretation

4. **Section D: Insights & Recommendations**
   - Key findings summary
   - Practical recommendations for engineers
   - Model improvement roadmap
   - Limitations and considerations

## Files
- `Manufacturing_AI_PreTest_RizalAgus.ipynb` - Main analysis notebook (73 cells)
- `drying_system_dataset.csv` - Pharmaceutical drying system data (200 samples)

## Requirements
```python
pandas >= 1.3.0
numpy >= 1.21.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
scikit-learn >= 0.24.0
jupyter >= 1.0.0
```

## Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Usage
```bash
jupyter notebook Manufacturing_AI_PreTest_RizalAgus.ipynb
```

## Dataset Features
- **Temperature_C**: Drying chamber temperature (°C)
- **Humidity_Percent**: Chamber humidity (%)
- **Airflow_Rate_m3h**: Air circulation rate (m³/h)
- **Pressure_kPa**: Chamber pressure (kPa)
- **Material_Moisture_Content**: Product moisture (%)
- **Drying_Time_min**: Total drying duration (min)
- **Control_Strategy**: Control system type (PID/Fuzzy/Adaptive)
- **Preheating_Time_min**: Warmup duration (min)
- **Steady_State_Achieved**: Process stability (0/1)
- **Energy_Consumed_kWh**: Total energy usage (kWh) - **TARGET**

## Key Features
✅ Professional visualizations with consistent styling  
✅ Data-driven decision justifications  
✅ Manufacturing context interpretation  
✅ Comprehensive documentation  
✅ Reproducible analysis (random_state=42)  
✅ Clean, well-commented code  

## Results
- Built and compared 3 predictive models
- Identified key energy consumption drivers
- Provided actionable recommendations
- Achieved strong model performance

## Author
**Rizal Agus Saini**  
Email: rizalagussaini.work@gmail.com  
GitHub: https://github.com/rizalagussaini

## License
This project is for educational and pre-test purposes.

---
*Manufacturing excellence through data-driven decision making.*
