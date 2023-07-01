# Cookie Cats A/B Testing Project

## About the Dataset

Cookie Cats is a popular mobile puzzle game developed by Tactile Entertainment. In this project, we analyze the results of an A/B test conducted in Cookie Cats to examine the impact of moving the first gate from level 30 to level 40. The primary focus is on player retention and game rounds to evaluate the effects of this change.

The dataset used for the analysis can be found on Kaggle.

## Dataset Overview

- The dataset consists of 44,700 observations for the gate_30 variation and 45,489 observations for the gate_40 variation.
- The median number of game rounds played by players in the gate_30 group is 17, while for the gate_40 group, it is 16.
- On average, players in the gate_30 group played approximately 52.46 game rounds, compared to an average of 51.30 game rounds for the gate_40 group.
- The standard deviation of game rounds for the gate_30 group is 256.72, indicating a relatively large spread of data points around the mean. In contrast, the gate_40 group has a standard deviation of 103.29, suggesting a smaller spread of data points.
- The maximum number of game rounds played by a player in the gate_30 group is 49,854, while in the gate_40 group, it is 2,640. This indicates that the highest number of game rounds played by a player in the gate_30 group is significantly larger than in the gate_40 group.

After removing the outlier (maximum value from the version starting at gate 30), the standard deviation for the gate_30 group decreased significantly from 256.72 to 102.06. As a result, the standard deviation for the gate_30 group is now closer to the standard deviation of the gate_40 group, making them more comparable in terms of data spread.

## Retention Rate

The retention rate in the experimental variation (gate_40) is 18.2%, while in the control variation (gate_30), it is 19.0%. This indicates that the control group has a slightly higher rate of user retention.

## Hypothesis Test

The results of the hypothesis test suggest that we reject the null hypothesis stating that "Moving the first gate from level 30 to level 40 in Cookie Cats has no significant impact on player retention and game rounds."

Based on these results, it can be concluded that moving the first gate from level 30 to level 40 in the mobile app has a negative impact on user retention. The control group, where the gate remains at level 30, shows higher retention rates compared to the experimental group with the gate at level 40.

## Summary

The A/B testing analysis of Cookie Cats reveals that moving the first gate from level 30 to level 40 in the mobile app leads to a decrease in user retention. The control group, where the gate remains at level 30, shows higher retention rates compared to the experimental group. These findings suggest that keeping the first gate at level 30 may be more favorable for user retention in the game.

Please explore the repository for detailed code and additional insights. If you have any questions or feedback, feel free to reach out to us.
