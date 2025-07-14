# Tackling Malnutrition in Africa: A Comprehensive Data Analysis
This project explores the socioeconomic and healthcare factors contributing to malnutrition across 45+ African countries, using data from the World Bank. The study formulates and tests four hypotheses related to food affordability, maternal education, immunization coverage, and GDP, applying statistical analysis and data visualization to derive actionable insights for policymakers.

---

## Project Overview
- **Objective:** Analyze and understand key indicators influencing malnutrition in African countries.
- **Data Source:** World Bank's World Development Indicators and Africa Data Indicators.
- **Approach:**
  - Cleaned and prepared raw `.csv` data using **Pandas**
  - Formulated four hypotheses based on public health and economic theory
  - Applied **Pearson** and **Spearman correlation** analysis with p-values to validate relationships
  - Visualized significant trends using **Matplotlib**
  - Drafted policy-oriented recommendations based on findings

## Key Hypotheses Tested
1. **Affordability vs. GDP per capita:** Negative correlation  
2. **Food Prices vs. Malnutrition Index:** Positive correlation  
3. **Immunization Rates vs. Malnutrition:** Negative correlation  
4. **Maternal Education vs. Malnutrition:** Negative correlation  

All hypotheses were supported by statistically significant results, indicating real-world policy relevance.

## Key Insights
- **GDP vs Food Affordability**: Countries with lower GDP per capita had significantly higher proportions of people unable to afford a healthy diet (Pearson: -0.79, p < 0.00000001). This supports the need for income support programs in low-GDP regions.
- **Food Prices vs Malnutrition**: A strong positive correlation (Pearson: 0.75, p < 0.0000002) revealed that rising food costs are linked to higher malnutrition rates, highlighting the need for price stabilization policies and improved agricultural infrastructure.
- **Immunization Rates vs Malnutrition**: Immunization coverage had a significant negative correlation with malnutrition (Pearson: -0.65, p < 0.00001), reinforcing that health access improvements can reduce undernutrition.
- **Maternal Education vs Malnutrition**: Female educational attainment (at least upper secondary level) was negatively associated with malnutrition (Pearson: -0.44, p = 0.0014), underscoring the importance of maternal education in long-term health outcomes.
These findings provide evidence-backed guidance for governments and health organizations aiming to reduce malnutrition through multi-sectoral interventions involving education, healthcare, and economic support.

## Repository Structure
- `Cleaned_Data.rar`: Cleaned dataset after preprocessing with Pandas  
- `Raw_Data.rar`: Original raw dataset downloaded from World Bank  
- `Code.ipynb`: Python notebook with data cleaning, hypothesis testing, and visualizations  
- `Paper_presentation.pptx`: Slide deck summarizing the project, insights, and recommendations  
- `Research_paper.pdf`: Full research paper detailing methodology, analysis, and future work  

## Tools & Libraries Used
- **Python** (Jupyter Notebook)
- **Pandas** for data cleaning
- **Matplotlib** for visualization
- **SciPy.stats** for correlation and hypothesis testing

## Data Access & Reuse
Due to size constraints, data is compressed into `.rar` archives.  
To access the full dataset or collaborate on future research, please reach out via GitHub or email.
