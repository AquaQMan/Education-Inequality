# Educational Inequality Study in the United States

# Description
This project focuses on studying what factors lead to educational inequality in the United States. These learning targets are met using linear regression and analysis of regression coefficients. In the end, free/reduced lunch was found to be the most telling feature in terms of predicting average ACT scores.

# Data
The data in this project comes from EdGap.org: https://www.edgap.org/#5/37.875/-96.987

Additional school data: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view

The data includes school type, school id, school level, unemployment rates, college percentages, marriage percentages, median incomes, average ACT scores, free/reduced lunch percentages, and the year and state in which the data was recorded.

# Data Processing
The data was first cleaned to include relevant features and joined on ID number. Negative percentages were dropped and imputation was performed on compatible columns. Then the data was split into a 70/30 train/test split and was normalized.

# Analysis Methods
Regression coefficients were used to determine what factors had the highest impact on average ACT scores. Data from the train set was then used and split by state to find local trends in median income. Those coefficients were later plotted by state, showing trends in the relationship of median income and average ACT by state.

# Author
This repository was created by Qasim Ali, a student at Seattle University studying data science.

# Licenses
The findings in this repository were made under the pretext of education, and as such can be used by anyone under the condition of attribution.
