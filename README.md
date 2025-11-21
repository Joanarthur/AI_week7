
# **COMPAS Bias Audit Project**

## 📋 Project Overview
This project analyzes racial bias in the COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) recidivism algorithm using IBM's AI Fairness 360 toolkit. The audit examines whether the algorithm exhibits disproportionate error rates across racial groups.

## 🎯 Objective
- Detect and quantify racial bias in risk assessment scores
- Visualize disparities in false positive/negative rates
- Provide remediation recommendations for fairer algorithms

## 📚 Theoretical Foundation
This practical implementation builds upon comprehensive theoretical research in AI ethics, covering:

Algorithmic bias and fairness metrics

Ethical principles in AI (justice, non-maleficence, autonomy, transparency)

Regulatory frameworks (GDPR, AI accountability)

Bias mitigation strategies and fairness tools

The complete theoretical assignment exploring these foundational concepts can be accessed here:
[AI Ethics Theoretical Assignmen](https://us.docworkspace.com/d/sIPDw-LxPy6uByQY?sa=601.1037)t

## 🛠️ Technologies Used
- **Python 3.x**
- **AI Fairness 360** (IBM's fairness toolkit)
- **pandas, numpy** (data manipulation)
- **matplotlib, seaborn** (visualization)
- **scikit-learn** (machine learning utilities)

## 📁 Project Structure
```
compas-bias-audit/
│
├── compas_bias_analysis.py      # Main analysis script
├── compas-scores-two-years.csv  # Dataset
├── compas_bias_analysis.png     # Generated visualizations
└── README.md                    # This file
```

## 🚀 Quick Start

### 1. Installation
```bash
pip install aif360 pandas matplotlib seaborn scikit-learn
```

### 2. Run Analysis
```python
python compas_bias_analysis.py
```

### 3. View Results
- Bias metrics in console output
- Visualization charts saved as PNG files
- Statistical analysis of disparities

## 📊 Key Metrics Analyzed
- **Statistical Parity Difference**
- **Disparate Impact Ratio** 
- **False Positive Rate Disparities**
- **Score Distribution by Race**

## 📈 Key Findings
The analysis reveals significant racial disparities:
- Higher false positive rates for African-American defendants
- Disparate impact ratio below acceptable thresholds
- Unequal distribution of "high-risk" classifications

## 💡 Remediation Strategies
1. **Algorithmic fixes**: Reweighing, prejudice remover
2. **Data preprocessing**: Bias detection and mitigation
3. **Model selection**: Fairness-aware algorithms
4. **Post-processing**: Equalized odds calibration

## 📄 License
Educational use - COMPAS data from ProPublica

