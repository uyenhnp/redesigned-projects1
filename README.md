# Redesigned Project - Unemployment Rates in the U.S. in September 2020

The objective of this project is to improve the graph below, which is displayed on the U.S Bureau of Labor Statistics website. 
<img src="https://github.com/uyenhnp/redesigned-projects1/blob/master/chart.png?raw=true" width="400">

The purpose of the original graph is to represent the unemployment situation in the U.S., including:
+ state-level unemployment rate in September 2020 (horizontal axis).
+ 12-month unemployment rate change from September 2019 to September 2020 (vertical axis).
+ number of unemployed persons in September 2020 (size of bubbles).

However, it does not provide an effective data visualization. 
+ Firstly, it’s difficult to compare the size among the bubbles.
+ Secondly, we cannot distinguish states which have the same base color. For instance, the base colors of Tennessee and New York are light blue.
+ Thirdly, there are a lot of overlapping circles near the vertical grid line at 6.0%.

Therefore, I propose to use the linked micromap and the choropleth map because they are more suitable for geographic data visualization. Additionally, they can reveal the pattern relating to regions and notice similarities and discrepancies between states.

Please refer to this [notebook](https://uyenhnp.github.io/projects/redesigned-projects.html) to see both code and explanation. 