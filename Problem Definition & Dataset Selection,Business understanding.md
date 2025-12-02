 Task 1: Problem Definition & Business Understanding
📌 Problem Statement
Chronic diseases such as diabetes, obesity, cancer, and heart disease are among the leading causes of death and disability in the United States. These conditions are influenced by behavioral risk factors like smoking, poor nutrition, and physical inactivity. Public health agencies need timely, state-level insights to design effective interventions and allocate resources.
This project aims to analyze the U.S. Chronic Disease Indicators (CDI) dataset to uncover trends, disparities, and actionable insights across states, years, and demographics.

🎯 Business Understanding
The Centers for Disease Control and Prevention (CDC) provides the CDI dataset to help public health professionals monitor chronic disease indicators across U.S. states and territories. These indicators support:
- Policy decisions at federal, state, and local levels
- Health program planning and evaluation
- Resource allocation for high-risk populations
- Public awareness and education campaigns
By analyzing this dataset, we can:
- Identify states with high prevalence of smoking, obesity, or diabetes
- Track how these indicators change over time
- Highlight disparities by age, sex, and race
- Support data-driven public health strategies

📂 Dataset Overview
- Source: CDC Chronic Disease Indicators
- Format: CSV
- Granularity: State-level, year-wise, stratified by demographics
- Key Columns:
- YearStart, YearEnd: Reporting year
- LocationDesc: U.S. state or territory
- Topic: Health category (e.g., Tobacco Use, Nutrition, Diabetes)
- Question: Specific indicator (e.g., "Adults who currently smoke cigarettes")
- DataValue: Measured value (percentage, rate, etc.)
- StratificationCategory1, Stratification1: Demographic breakdowns (e.g., Age, Sex, Race)
- DataValueType: Type of value (e.g., crude rate, age-adjusted rate)
- LowConfidenceLimit, HighConfidenceLimit: Statistical confidence bounds

💡 Analytical Goals
- Clean and structure the dataset for analysis
- Visualize trends in chronic disease indicators across states and years
- Compare prevalence across demographic groups
- Generate insights to support public health decision-making

