# RAINBOW-SIX-SEIGE-EXPLORATORY-DATA-ANALYSIS
Using the R6 velvet shell data set, we're attempting to uncover hidden trends and patterns in operators, maps, game types, and other variables in order to identify the greatest and worst operators, as well as the finest weapons and attachments.

## Abstract
R6 is a widely played multiplayer shooting video game in which players take on the roles of attackers or defenders. Using the R6 velvet shell data set, we're attempting to uncover hidden trends and patterns in operators, maps, game types, and other variables in order to identify the greatest and worst operators, as well as the finest weapons and attachments. This in-depth understanding would also aid gamers and game developers in comprehending the operators' and maps' strengths and limitations.

## Aim of the project
1. In each map, which are the most lethal attacker and defender operators? Is there any operator overpowered compared to others?
2. Which is the best primary weapon for the top three attacker and defender operator and the best accessories that can be fitted to the primary weapon to increase the kill?
3. There are numerous reasons for the team to win a round. Find out the best round win reasons.

## Data
The dataset is collected directly from ubisoft website.
https://www.ubisoft.com/en-us/game/rainbow-six/siege/news-updates/2fQ8bGRr6SlS7B4u5jpVt1/introduction-to-the-data-peek-velvet-shell-statistics

1. dataDump_s5_summary_operator_loadout.csv
  * Expertise level required – Amateur
  * Size of the file – 39MB
  * Major attributes – Platform, skill rank, operators and role, primary and secondary weapon, wins, kills, deaths, picks

2. dataDump_S5_summary_objectives.csv
* Expertise level required – Professional
* Size of the file – 767MB
* Major Attributes – Platform, Game mode, Maps, Skill rank, Operators and role, wins, kills, deaths, picks etc

3. dataDump_S5.csv
* Expertise level required – Expert
* Size of the file – 19.3 GB
* Major attributes – Platform, game modes and maps, win role, reason for victory, operators and roles, weapons, weapon attachments, kills, deaths, picks, wins etc

## Analytical Methods
For exploratory data analysis, bar plots, lollipop plots and heatmaps are used. These plots were drawn with the help of three different python libraries. These are matplotlib, seaborn and plotly. Seaborn was mainly used to plot heatmaps because of the ease of plotting heatmaps with it. The other two were used to plot bar plots and lollipop graphs.
Bar plots are plots used to compare different items with respect to a dependent variable. In this project, bar plots are mainly used to compare different operators with respect to a dependent variable, which can be the kill ratio, win ratio or just the number of kills. Lolli pop plots are used to plot kill ratio with respect to different operators. Heatmaps are used in various occasions. It is used to compare maps and operators with respect to kill ratio, or to compare maps and winning reasons with respect to the number of round wins.
Other statistical analysis methods used are mainly mean and maximum values. In various stages of the analysis, mean of kill ratio and win ratio has been taken with respect to different game modes, maps and operators. In other times, the maximum value of kills or wins has been taken with respect to different categories.

## Results
* Heat map of attacking operators vs map

![attack_real](https://user-images.githubusercontent.com/115481947/210448609-1d28a17f-be93-4eb4-853f-445e7854389d.png)

* Heat mp of defending operators vs map

![defenD_real](https://user-images.githubusercontent.com/115481947/210448647-1111e4c2-20b0-4e6a-b883-6559c1eac25f.png)

