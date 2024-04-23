# Purpose
This project focuses on trying to predict what factors lead to educational inequality in the United States.

# Data
The data in this project comes from EdGap.org: https://www.edgap.org/#5/37.875/-96.987

Additional school data: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view

# Preparation
The data was first cleaned to include relevant features and joined on ID number. NaN's and negative percentages were dropped and imputation was performed on compatible columns. Then the data was split into a 70/30 train/test split.
