# Hospital-Administration-System

## 📊 Project Overview

This project analyzes hospital administration data to identify patterns and factors associated with high readmission rates. As a data analyst working on improving patient care quality, this analysis addresses the critical challenge of reducing unnecessary hospital readmissions while optimizing healthcare resource allocation and compliance with healthcare regulations.

## 🎯 Objective

The primary goal is to analyze hospital admission data from Novartis hospital to:
- Identify patterns contributing to high readmission rates
- Uncover factors associated with patient readmissions within 30 days
- Provide actionable insights for targeted interventions
- Improve patient outcomes and reduce healthcare costs

## 📁 Dataset Information

**Data Source:** [Hospital Administration Data - Kaggle](https://www.kaggle.com/datasets/shivavashishtha/hospital-administration-data/)

### Data Dictionary

| Column | Description |
|--------|-------------|
| `encounter_id` | Unique identifier of an encounter |
| `patient_id` | Unique identifier of a patient |
| `race`, `gender`, `age` | Demographic information |
| `weight` | Patient's weight (mostly missing, denoted by ?) |
| `time_in_hospital` | Length of hospital stay in days |
| `medical_specialty` | Specialty of the admitting physician |
| `num_lab_procedures` | Number of lab tests performed |
| `num_procedures` | Number of procedures (other than lab tests) performed |
| `num_medications` | Number of distinct medications prescribed |
| `number_outpatient` | Number of outpatient visits in the year preceding the encounter |
| `number_emergency` | Number of emergency visits in the year preceding the encounter |
| `number_inpatient` | Number of inpatient visits in the year preceding the encounter |
| `diag_1` to `diag_5` | Primary and secondary diagnoses codes |
| `number_diagnoses` | Number of diagnoses entered into the system |
| `X1` to `X25` | Indicators for various medications |
| `change` | Indicates if there was a change in diabetic medications |
| `diabetesMed` | Indicates if any diabetic medication was prescribed |
| `readmitted` | Target variable: patient readmitted (<30 days = 1, else = 0) |

## 🔍 Analysis Components

### Analysis
- Distribution of readmission rates across different age groups
- Average length of hospital stays by medical specialty
- Correlation between emergency visits and readmission rates
- Diabetes patient readmission analysis
- Impact of diabetic medication changes on readmissions
- Relationship between lab procedures and readmission rates
- Demographic analysis of readmission rates (race and gender)
- Weight category distribution and readmission correlation
- Medication impact on hospital stay length
- Outpatient visit frequency impact on readmissions

## 🛠️ Tools & Technologies

- **Microsoft Excel**: Data cleaning, analysis, and visualization
- **Power Query**: Data transformation and preprocessing
- **Pivot Tables**: Summary statistics and cross-tabulation analysis
- **Excel Functions**: Statistical calculations and data manipulation

## 📈 Key Insights

This analysis provides insights for multiple stakeholders:
- **Hospital Board**: Operational costs, revenue trends, and quality metrics
- **C-Suite Executives**: Capacity planning and resource optimization
- **Department Heads**: Staffing levels and patient flow improvement
- **Clinicians**: Treatment outcomes and evidence-based decision-making
- **Patients**: Improved care quality and reduced readmission risks

## 💡 Business Impact

- Enhanced patient care quality through targeted interventions
- Optimized hospital resource allocation
- Reduced unnecessary readmissions and associated costs
- Improved compliance with healthcare regulations
- Better patient outcomes and hospital reputation

## 🚀 Getting Started

1. Download the dataset from the Kaggle link provided above
2. Open the Excel workbook `Hospital_Administration_Analysis.xlsx`
3. Navigate through different worksheets for various analysis levels
4. Review pivot tables and charts for visual insights

## 📊 Analysis Methodology

1. **Data Cleaning**: Handling missing values, particularly in the weight column
2. **Exploratory Data Analysis**: Understanding distributions and patterns
3. **Statistical Analysis**: Correlation analysis and hypothesis testing
4. **Segmentation**: Grouping patients by demographics and clinical factors
5. **Visualization**: Creating charts and dashboards for insights
6. **Insights & Recommendations**: Actionable findings for stakeholders

## 👤 Author

**Pratyush Puri**  
Data Analyst Intern @ Jobaaj

## 📝 License

This project is available for educational and analytical purposes.

## 🤝 Acknowledgments

- Dataset provided by [Shiva Vashishtha on Kaggle](https://www.kaggle.com/datasets/shivavashishtha/hospital-administration-data/)
- Hospital Administration Case Study Framework

---

*For questions or collaboration opportunities, feel free to reach out!*


