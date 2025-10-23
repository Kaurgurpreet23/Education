# ACT SCORES AND SOCIOECONOMIC FACTORS
This report investigates the relationship between student–teacher ratios and student academic performance across 20 U.S. states. The goal is to understand whether states with smaller class sizes (lower student–teacher ratios) tend to perform better on standardized tests such as the ACT. This question matters for education policymakers and administrators who must allocate resources efficiently while improving student learning outcomes. By analyzing publicly available datasets, the project explores whether smaller classes correlate with stronger academic results.
In addition to this, I will examine the relationship between the average ACT score and the five socioeconomic predictor variables in the EdGap data set to check which socioeconomic predictor variable has closer relationship or effect on a student’s performance in the 20 states we have data from.

> 

---

## Project Overview



- **Objective:** Examining the relationship between the average ACT score and the five socioeconomic predictor variables in the EdGap data set accessed from the GitHub Repository brian-fischer/DATA-5100. Another variable was added to check if the student-teacher ratio is a better predictor for interpreting better ACT scores in the 20 states, we have data from.
- **Domain:** Education
- **Key Techniques:** The methodologies used were exploratory data analysis, single input linear regression, quadratic polynomial linear regression and multiple regression alongside OLS results to interpret results.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** C:\Users\gillm\OneDrive\Desktop\MSDS\DATA 5100\Education\data,
- School Information Data Set from  National Center for Education Statistics - https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=1
- EdGap Data Set from GitHub Repository brian-fischer/DATA-5100
- Student-Teacher Ratio Data Set from National Center for Education Statistics - https://nces.ed.gov/ccd/elsi/tableGenerator.aspx?savedTableID=651538

- **Description:**  Examining the relationship between the average ACT score and the five socioeconomic predictor variables in the EdGap data set and toif the student-teacher ratio is a better predictor for interpreting better ACT scores in the 20 states
- **License:** (if applicable)

---

## Analysis

The regression analysis revealed a weak but statistically significant negative relationship between student–teacher ratio and ACT averages (R² » 0.03 across states). Scatter plots confirmed a slight downward trend, indicating that as the student–teacher ratio increases, average ACT performance tends to decrease marginally. However, variability across states suggests that other contextual factors such as funding, socioeconomic conditions, and curriculum also play a major role.

In the multiple regression model, percent lunch remained a statistically significant variable even after controlling for others — confirming its robustness as a socioeconomic indicator linked to performance disparities.
The key statistical findings indicate that the percent of adults with a college degree is the strongest positive predictor of ACT scores. Conversely, the percent of students with free or reduced lunch, referred to as percent lunch, is the strongest negative predictor of ACT scores. Median income also shows a positive correlation, though its effect is overlapped by educational attainment. Additionally, the percent of married adults had weak or statistically insignificant effects on ACT scores.

## Results

This analysis demonstrates a modest negative correlation between student–teacher ratios and ACT performance at the state level. While smaller class sizes appear to offer benefits, effective educational improvement requires multifaceted policy approaches. The student-teacher ratio is not a strong predictor to analyse the ACT scores.From the comparative analysis of the five socioeconomic variables, economic disadvantage (percent lunch) emerged as the most consistent and influential predictor of student performance.

## Authors

- Your Name - [@Kaurgurpeet23](https://github.com/Kaurgurpreet23)
---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Jupyter Notebook 
- Google Colab
- Microsoft Word
- Adobe Acrobat
- Github Repository
