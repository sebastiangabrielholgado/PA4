# PA4 SEBASTIAN GABRIEL Y. HOLGADO
This Python Assignment deals with the use of Data Wrangling and Data Visualization
For starters: import seaborn, pandas and matplotlib libraries for the following problems
```
import pandas as pd

import seaborn as sns

import matplotlib.pyplot as plt
```
# 1) Create the following data frames based on the format provided:
> Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas

> a) Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant Instrumentation and hometown Luzon

> b) Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female

- In this problem, it is supposed to return only certain data in the data frame along with the given conditions
- I then tried using conditional statements using conditional operators such as `&` and `==` and `>` to set conditions and meet the required data


# 2) Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score?
- In this part, I created a boxplot to easily show the data that is given above for easy comparison.
- I mainly used the sns and the matlib libraries in order to create the graphs which is something I had to research further in order for me to create the charts.
- I then created a boxplot from the library of Seaborn then I manipulated the features to make it more presentable and readable

#### Version History:
##### [v1.1.0] - 9/17/2025
##### [v1.2.0] - 9/23/2025
###### Changes:
- Improved the title of the graphs
- Updated the style of the graph
- Adjusted the font sizes
- Added labels to the x and y axis
