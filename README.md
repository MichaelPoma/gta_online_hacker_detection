# Project for NYU 2022 Rockstar Games Datathon

**Video Presentation: https://www.youtube.com/watch?v=J-MgDZAGmy0**

This project is a submission for the NYU 2022 RockStar Datathon for the Sandbox Challenge.

Our goal was to detect suspicious accounts on the Grand Theft Auto Online dataset.

We identified suspicious players based on their player activity and our personal experiences with the game. We developed a confidence interval to determine a user’s change in rank for a given game session, and if their rank had exceeded the upper bound, they were deemed suspicious. We then developed 5 models to classify these suspicious accounts, and determined the best based on performance and the nature of the models.

We deemed the best model fit for scalability was our AdaBoost with an AUC score of 0.810.

Our recommendations to expand upon the project would be to specifically analyze the behavior of suspiciously flagged accounts, and to increase the span of data analyzed to draw more conclusions and determine a wider array of flagging metrics.
