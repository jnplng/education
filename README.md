# Education Project

## Project Overview
Is school performance, measured by ACT score, predicted by socioeconomic factors? This is 
the question asked in this project. The goal of this project is to discover what socioeconomic 
factors predict average ACT score.

The data is from EdGap.org, eddataexpress.ed.gov, and the National Center for Education Statistics. It includes average ACT score by school and socioeconomic factors.

The findings were that the socioeconomic factors of unemployment rate, percentage of adults with a college degree, 
and percentage of students at the school eligible for free or reduced lunch together predict 
academic success by predicting the average ACT score of the students at the school.


- **Objective:** The main goal of the project is to determine whether socioeconomic factors can predict academic success.
- **Domain:** Education
- **Key Technique:** Regression

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

- **Source:** (https://github.com/brian-fischer/DATA-5100/blob/main/EdGap_data.xlsx) 
            (https://www.dropbox.com/scl/fi/fkafjk8902sq8ptxh94r2/ccd_sch_029_1617_w_1a_11212017.csv?rlkey=gucrdz5f6e38bezz2y3yalxbw&e=1&dl=0)
            SY1617_FS195_DG814_LEA.csv from https://eddataexpress.ed.gov/download
- **Description:** The EdGap.org data includes average ACT score, unemployment rate, percentage of adults with a college 
degree, percentage of children in a married couple family, median household income in dollars, 
and percentage of the students at the school eligible for free or reduced lunch. The data from the National Center for Education Statistics includes
the  school year, the state, the school name, the school ID number, the school district ID number, the zip code, the type of school, and 
the school level (such as high school or elementary school). The data from Data Express includes the number of homeless students in 
the school district and the school district ID. The EdGap file is an Excel worksheet. The other data sets are .csv files. The National Center for 
Education Statistics file is almost 40,000 KB. The other two data files are around 1000 KB.
-
---

## Analysis

The analysis was performed in Jupyter Notebook. The code should be run in order to reproduce the results.

---

## Results

Multiple regression showed that the unemployment rate, percentage of adults with 
a college degree, and percentage of the students at the school eligible for free or reduced lunch 
together were the best predictors of average ACT score, based on the R-squared of 0.628. 
This implies that the unemployment rate, percentage of adults with 
a college degree, and percentage of the students at the school eligible for free or reduced lunch
can predict academic success, as measured by ACT score.

---

## Authors

- Jennifer Poling - (https://github.com/jnplng/education)
---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: Jupyter Notebook, Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, Statsmodels
- Tutorials or papers referenced: Seattle University DATA 5100 education tutorial by Brian Fischer

