Fake Instagram Account Analysis – Tableau Report

Objective
To identify behavioral patterns that distinguish fake from real Instagram accounts using visual analytics in Tableau.

Dataset Overview
- Source: Labeled account data with 12 key features.
- Size: 576 labeled records (train.csv), 120 unlabeled (test.csv).

Visual Insights

Class Distribution
- Dataset is moderately balanced between fake (252) and real (324) accounts.

Profile Picture vs Fake
- Majority of fake accounts lack profile pictures.
- Real accounts are more likely to have a profile image.

Followers vs Follows (Scatter Plot)
- Fake accounts typically have low followers but follow many others.
- Real accounts cluster with higher follower/follow ratios.

Description Length
- Fake accounts often have shorter bios or none at all.
- Real users provide longer, more descriptive profiles.

Privacy Analysis
- Fake accounts are more likely to be private.

Follower/Following Ratio
- Real accounts tend to maintain a balanced ratio.
- Fake accounts have abnormally high or low ratios.

Conclusion
Key indicators of fake accounts:
- Missing profile picture
- Short or no bio
- High following count but low followers
- Private account status
- Unusual follower/following ratios
