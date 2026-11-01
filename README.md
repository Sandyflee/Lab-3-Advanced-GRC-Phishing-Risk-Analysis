# Lab 3: Advanced GRC Phishing Simulation & Quantitative Risk Analysis

## Overview
This lab analyzes three phishing simulations conducted at GlobalTech Inc. The analysis calculates phishing metrics, quantifies financial exposure, evaluates security controls, calculates ROI, performs statistical analysis, and provides executive-level recommendations.

## Dataset
- Total employees: 2,000
- Average employee salary: $85,000/year
- Estimated cost of a major data breach: $4,350,000
- Probability of a major breach following credential theft: 25%

## Campaigns
| Campaign | Target | Emails Sent | Opened | Clicked | Credentials | Data Entry |
|---|---:|---:|---:|---:|---:|---:|
| A - HR Bonus Notification | 100 | 100 | 82 | 47 | 18 | 5 |
| B - IT System Password Reset | 250 | 250 | 200 | 150 | 75 | 25 |
| C - CEO Urgent Document Review | 80 | 80 | 72 | 60 | 12 | 8 |

## Key Findings
- Campaign B had the highest credential submission rate: **30%**.
- Campaign C had the highest open-to-click conversion: **83.3%**.
- Campaign B had the highest post-click credential submission rate: **50%**.
- Projected credential exposure from Campaign B: **600 employees**.
- Expected breach events under the lab assumptions: **150**.
- Estimated financial exposure: **$652,500,000**.
- MFA modeled ROI: **724,175%**.
- Security awareness training modeled ROI: **391,400%**.
- $490,000 total investment breaks even at approximately **0.113 avoided breaches**; preventing one major breach exceeds the investment.

## Important Calculation Note
The original worksheet gives Campaign A exposure as $156.6M and Campaign C exposure as $104.4M. Using the worksheet's stated formula, the mathematically correct figures are:
- Campaign A: 360 × 25% × $4.35M = **$391.5M**
- Campaign C: 300 × 25% × $4.35M = **$326.25M**

These corrected calculations are used in this submission.

## Files
1. `Phase-1-Basic-Metrics.md` - fundamental and efficiency metrics
2. `Phase-2-Risk-Quantification.md` - exposure, ALE, and control ROI
3. `Phase-3-Risk-Assessment.md` - risk matrix and statistical analysis
4. `Phase-4-Executive-Briefing.md` - executive report
5. `Control-Recommendations.md` - recommended controls and ROI

## Conclusion
The analysis supports immediate enterprise-wide MFA, targeted security awareness training, advanced email protection, continuous monitoring, and behavioral analytics as a layered human-risk management strategy.
