Instagram Fake Account Detection – Tableau Dashboard

This project analyzes Instagram account data using Tableau to detect patterns between fake and real accounts.

## 📊 Files Included
- `train.csv`: Labeled dataset (576 entries) with account features and fake/real label.
- `test.csv`: Unlabeled dataset (120 entries) for prediction/testing.
- `Dashboard 1.pdf`: Exported Tableau dashboard visualizing key metrics.
- `README.md`: Project documentation.
- `Report.pdf`: Executive summary and insights.

## 📁 Dataset Features
| Column                 | Description                                      |
|------------------------|--------------------------------------------------|
| profile pic            | 1 if present, 0 if not                           |
| nums/length username   | Digits per username length ratio                 |
| fullname words         | Number of words in full name                     |
| nums/length fullname   | Digits per full name length ratio                |
| name==username         | 1 if name equals username                        |
| description length     | Bio length (characters)                          |
| external URL           | 1 if external URL exists, 0 if not               |
| private                | 1 if account is private                          |
| #posts                 | Total number of posts                            |
| #followers             | Total number of followers                        |
| #follows               | Total number of accounts followed                |
| fake                   | Label: 1 = fake, 0 = real                         |

## 📈 Dashboard Overview
Key visualizations include:
- Class Distribution (Fake vs Real)
- Profile Picture vs Fake Status
- Followers vs Follows (scatter plot)
- Description Length vs Fake
- Follower/Following Ratio Analysis
- Bio Length Distribution

## 🚀 How to Use
1. Open Tableau Desktop or Public.
2. Load `train.csv`.
3. Use dashboard filters and charts to explore account patterns.
4. Optional: Upload `test.csv` for prediction or evaluation.

## 🧠 Insights Summary
See `Report.pdf` for detailed analysis and findings.