 A/B Testing: Hypothesis Testing

 Project Overview:
This project evaluates the statistical significance in the difference in players between two different versions of the mobile puzzle game "Cookie Cats." The A/B test focuses on the impact of moving the first gate in Cookie Cats from level 30 to level 40 on player retention and game rounds.

 Dataset Description:
The dataset includes player information such as user IDs, game versions (gate_30 or gate_40), the number of game rounds played, and player retention after 1 and 7 days of installing the game.

 Exploratory Data Analysis:
- Checked for missing values (No missing values found).
- Removed outliers in the `sum_gamerounds` column.
- Visualized the number of players for each version on graphs.
- Analyzed summary statistics and player retention rates.

 Hypothesis Testing:
- Applied Shapiro-Wilk tests for normality assumption.
- Utilized Mann-Whitney U test for non-parametric comparison between two groups (gate_30 and gate_40).
- Failed to reject the null hypothesis, indicating no statistically significant difference between the two groups regarding player retention and game rounds after moving the gate.

 Conclusion:
The A/B testing results suggest that moving the first gate from level 30 to level 40 in Cookie Cats did not significantly impact player retention or game rounds. Further analysis may be warranted to explore other factors affecting player engagement in the game.
