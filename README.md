# Descriptive and Inferential Statistics To Determine Performance of Lecture Theatres in University

* This is a real-life project that I completed using Excel in 2020 during my MSc and improved it using Python in 2021.
* The project used decriptive and inferential statistics on 3953 student questionnaires, received over 50 lectures to determine performance of lecture theatres as a learning environment. 
* Three types of data were analyzed: students properties (gender, clothing, seat position), students perception/KPI (thermal comfort, lecture theatre rating, etc.) and lecture theatre environmental and physical properties (mean temperature, room length etc.)
* The analysis identified the performance of lecture theatres and proposed improvements to few under-performing lecture theatres

## Code used

### Python version: 3.8.8
### Packages: pandas, numpy, scipy, seaborn, matplotlib, plotly, missingno

## Data

The data was provided by the university and required a lot of cleaning. 
There were mixed data types in columns that should be numerical, columns that needed to be deleted as those variables were not going to be analyzed, columns that needed consistent data ('F' for females not 'f'), deleting values that are not expected in a variable.
Missing values were visualized and it was found that empty cells were negligible.

## Descriptive Statistics

The following recommendations were proposed based on descriptive statistics:
* Overall the learning environment of 50 lecture theatres in University College London is impressive. In all KPI's, the data was skewed to favour high points.
* Best and worst performing lecture theatres were identified after their repeated positings in KPI's. Out of 30 lecture theatre features, only seat comfort, desk space, room length/width, mean room temperatures and light intensities presented some correlation, although, weak. The following recommendation is therefore provided to improve poor performing lecture theatres: seat width around 500mm, deskp depth around 325mm, 750mm desk height, lecture theatre length and width around 12.5m, room height 2.5m and 20-24 degrees of room temperature.


## Inferential Statistics

An independent, two-tailed t-test and a one-way ANOVA was carried out (all assumptions were justified), the following conclusions were reached:
* Male thermal perception (felt hotter) had significantly higher values (4.11 ± 0.06 (no units)) compared to female thermal perception (3.93 ± 0.04) (p-value < 0.05). However, a score of 4 indicates a neutral thermal sensation, which both means are close to.
*  There was no statistical evidence that thermal perception between the front, middle and back seated students differs as the p-value was slightly over 0.05 (0.06).

