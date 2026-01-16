# 🎓 Bursary Investment Analysis Dashboard

A data-driven decision support tool for optimizing bursary funding allocation using school performance metrics and predictive analytics.

## 📊 Project Overview

This Streamlit application analyzes school performance data to identify where bursary funding delivers the highest probability of learner success per rand invested. The tool supports evidence-based decision-making for educational funding committees and CSR investment boards.

## ✨ Key Features

### 🔍 **Intelligent School Categorization**
- **Group A: High Impact / Best ROI**: Quintile 1-2 schools with ≥80% pass rate
- **Group B: Stable / Scalable**: Quintile 3 schools with ≥75% pass rate
- **Group C: High Potential**: Schools with ≥60% pass rate needing support
- **Group D: High Risk**: Schools below threshold requiring intervention

### 📈 **Advanced Analytics**
- **Investment Score Algorithm**: Weighted combination of pass rate and socio-economic factors
- **Performance Gap Analysis**: Actual vs. expected performance based on quintile
- **Risk Assessment**: Automated risk level classification (Low/Medium/High)
- **Impact Potential**: Calculates total successful learners per school

### 🎯 **Decision Support Tools**
- **Funding Recommendations**: AI-powered funding strategies per school category
- **Provincial Analysis**: Regional performance comparisons
- **Over/Under Performer Identification**: Spotlights exceptional schools
- **Executive KPIs**: Real-time metrics for quick decision-making

## 🛠️ Technology Stack

- **Frontend**: Streamlit (Interactive web dashboard)
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Data Source**: Excel files (Openpyxl backend)
- **Deployment**: Streamlit Cloud, Docker, or local hosting



## 📊 Dashboard Components

### 1. **Executive KPIs**
- Total schools analyzed
- Average pass rate
- Best ROI schools count
- High-risk schools count
- Average investment score

### 2. **Investment Group Breakdown**
- Visual distribution of schools across A, B, C, D categories
- Bar chart for quick assessment

### 3. **Group A - Best ROI Schools**
- Detailed table of highest potential schools
- Sortable by investment score

### 4. **Provincial Analysis**
- Comparative performance across provinces
- ROI distribution by region

### 5. **Performance Gap Analysis**
- Overperforming vs. underperforming schools
- Identifies schools exceeding socio-economic expectations

### 6. **Risk Assessment**
- High-risk school identification
- Funding recommendations with interventions

## 🔧 Advanced Features

### Investment Algorithm
```python
# Core investment scoring logic
Investment_Score = (Pass_Rate × 0.6) + ((6 - Quintile) × 10 × 0.4)
```

### Performance Gap Calculation
```python
Expected_Pass = Quintile × 15 + 40
Performance_Gap = Actual_Pass_Rate - Expected_Pass
```

### Impact Potential Metric
```python
Impact_Potential = Total_Achieved × (Pass_Rate / 100)
```


## 📈 Business Impact

This tool helps organizations:
- **Maximize ROI** on educational investments
- **Reduce risk** of bursary failure
- **Improve equity** by targeting disadvantaged schools
- **Make data-driven decisions** with real-time analytics
- **Track impact** over time with exportable reports

## 📄 License

MIT License

**Empowering education through data-driven decisions** 🎓📊
