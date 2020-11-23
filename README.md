# COVID_prejudice
## This repository shows the data-cleanup process for a research project done by Portland State University.

#### Empirical findings revealed an inverse association between prejudice and COVID safety behaviors. That is, individuals who are more prejudiced are less likely to follow COVID safety guidelines.

#### This repository shows the process used to clean the data. Disclosure: I do not show the dataframe itself, since it contains IP addresses. This is sensitive material and we are committed to the privacy of our participants.

### Data_cleanup
##### The purpose of this jupyter notebook file is to identify real responses, and reject fake responses (bots, people that did not pay attention). It does the following:
##### - Identifies participants that passed all attention checks
##### - Identifies people who have real human dimensions
##### - Identifies people who reported the same age value at the beginning and the end of the questionnaire.

### Data_cleanup 2
##### This jupyter notebook file eliminates participants that were rejected on MTurk. It does the following:
##### 1. Stores the IDs of participants who were rejected
##### 2. Creates a dataframe for the rejected participant
##### 3. Creates a dataframe for the participants that were not rejected
##### 4. Verifies that the manipulation worked by identifying repeated IP addresses. This manipulation check verifies that each IP address was unique, thus confirming that the responses come from different individuals.
