Summary -
This visualization plots the survival percentage of male and female passengers in titanic. The survival percentage for female passengers are 74% where male passengers are only 19%. This shows female passengers got priority compared to male passengers. Further plotting survival percentage of female, male for each class reveals that most of the female passengers in class:1 (97%) and class:2 survived (92%). Where most of the male passengers in class_2 (84%) and class_3 (86%) didn't survive.

Design -
In this visualization, I want user to explore Survival Percentage Vs different demographic information. So, the select box enable user to plot Survival Percentage Vs Gender or Passenger Class.

In the plot, Survival Percentage Vs Sex, survival percentage is a continuous variable in the range 1 to 100 and Sex is a categorical variable with values male and female. The relationship I want to show is the fraction of male survived & perished; similar statistics for female. To compare survived & perished percentage for male/female, I weighted between 2 chart types Pie chart & Stacked bar chart. Since Stack bar charts are easier to interpret and compare, I choose stacked bar chart.

In the plot, Survival Percentage Vs Pclass, I want to show survival percentage for all passengers of a class, only female passengers & only male passengers. So I need to encode 3 variables on the chart. These variables are Survival percentage, Pclass & Sex(all, male, female). Since Survival percentage & Pclass are the most important variabes they are represented by Y-Axis & X-Axis. I tried to represent the survival percentage using a bar chart. But since I want to show the trend or survival with Pclass, the trend is better represented in a line chart. I use muti-line chart to show the trend of total, female & male passenger Survival Percentage with Pclass. To represent the 3rd variable (Sex) in this chart I used color that encodes all (in grey), male (in blue) & female (in pink). I used blue & pink for male & female as it is very common color used in public transport (buses, trains) or facilities (washroom) to differentiate genders.

Feedback -
index_1.html: It doesn't reveal if female passengers of all classes survived equally
index_2.html: Viewers needs control to choose visualization of overall survival (big picture) or survivals by classes (detailed picture)
index_3.html: Add few lines to give context of the visualisation. Change tool-tips from "survived as 0/1" to more meaningful text. 

Resources - 
https://www.w3schools.com/
http://www.w3resource.com/javascript/javascript.php
http://dimplejs.org/examples_index.html
https://stackoverflow.com/questions/10784018/how-can-i-remove-or-replace-svg-content
https://stackoverflow.com/questions/13299024/hiding-a-check-box-in-html
