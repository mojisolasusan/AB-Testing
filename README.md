# AB-Testing
A/B testing, also known as split testing, is a method used to compare two versions of a webpage, app, or other marketing asset to determine which one performs better. This technique involves dividing the audience into two groups: one group is shown version A, and the other group is shown version B.

### Project Description
Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three" style puzzle game where the player must connect tiles of the same color in order to clear the board and win the level.

### Data Description
The data is from 90,189 players that installed the game while the AB-test was running. The variables are:
userid - a unique number that identifies each player.
version - whether the player was put in the control group (gate_30 - a gate at level 30) or the test group (gate_40 - a gate at level 40).
sum_gamerounds - the number of game rounds played by the player during the first week after installation
retention_1 - did the player come back and play 1 day after installing?
retention_7 - did the player come back and play 7 days after installing?
When a player installed the game, he or she was randomly assigned to either gate_30 or gate_40.

### AB Testing Process
Understanding business problem & data
Detect and resolve problems in the data (Missing Value, Outliers, Unexpected Value)
Look summary stats and plots
Apply hypothesis testing and check assumptions
Check Normality & Homogeneity
Apply tests (Shapiro, Levene Test, T-Test, Welch Test, Mann Whitney U Test)
Evaluate the results

### Conclusion
Briefly, There are statistically significant difference between two groups about moving first gate from level 30 to level 40 for game rounds.

 Which level has more advantages in terms of player retention?
1-day and 7-day average retention are higher when the gate is at level 30 than when it is at level 40.
