# quant-venture-capital-ressources
This bounty represents the initial phase of a series of iterations, collectively known as "Rally". Each Rally features a short submission phase (up to one month), aimed at enhancing our Data-Generating Process. The steps involved in each Rally include the release of a new dataset version, model submission, out-of-sample scoring, result analysis, and the subsequent release of the next dataset version. This process will be repeated until the desired level of accuracy is achieved.
‍
We will release only a fraction of the data for a number of reasons: first, some of the data is kept on-hold for the next "Rallies" and for out-of-sample scoring. Secondly, the size of the dataset is challenging (1.5 TB): it would require significant computing resources not readily available to most community members.


# One month Machine Learning Bounty
One month to submit your best supervised machine learning model to categorize Startups that are likely to perform an upround (Pre-Seed to Seed, to Serie A, to Serie B, to Serie C etc.)

# Problem Statement
We categorized startups to enable participants to develop supervised learning algorithms. Startups labeled as 1 are expected to achieve higher valuations, while those labeled as 0 are not anticipated to experience significant valuation growth.

# Scoring
To assess the AI's performance effectively, we will compute its F1 score. This metric balances the precision (true positives identified by the algorithm) and recall (accounting for missed opportunities). For the algorithm to demonstrate its effectiveness, it must accurately identify investment opportunities while minimizing false negatives and false positives. The F1 score will provide a comprehensive view of the algorithm's accuracy and reliability.
