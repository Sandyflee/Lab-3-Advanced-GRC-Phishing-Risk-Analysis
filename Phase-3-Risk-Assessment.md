# Phase 3: Comprehensive Risk Assessment

## Step 6: Risk Assessment Matrix

| Campaign | Risk Level | Credential Rate | Projected Employees | Expected Breaches | Financial Exposure | Priority | Recommended Action |
|---|---|---:|---:|---:|---:|---:|---|
| A - HR Bonus | Medium-High | 18% | 360 | 90 | **$391.5M** | 2 | Enhanced Training |
| B - IT Password Reset | Critical | 30% | 600 | 150 | **$652.5M** | 1 | Immediate MFA |
| C - CEO Document Review | High | 15% | 300 | 75 | **$326.25M** | 2 | Executive Training |

### Campaign A Calculation
2,000 × (18/100) = 360 employees

360 × 25% = 90 expected breaches

90 × $4,350,000 = **$391,500,000**

### Campaign B Calculation
2,000 × (75/250) = 600 employees

600 × 25% = 150 expected breaches

150 × $4,350,000 = **$652,500,000**

### Campaign C Calculation
2,000 × (12/80) = 300 employees

300 × 25% = 75 expected breaches

75 × $4,350,000 = **$326,250,000**

### Note on the Original Worksheet
The supplied worksheet lists $156.6M for Campaign A and $104.4M for Campaign C. Those values do not match the formula provided in the worksheet. The corrected calculations above are used because they directly follow the stated formula.

## Step 7: Statistical Significance

### Campaign A 95% Confidence Interval

Given:
- p = 0.18
- n = 100
- z = 1.96

Formula:

Margin of Error = 1.96 × √[p(1-p)/n]

= 1.96 × √[(0.18 × 0.82)/100]

= 1.96 × √0.001476

= 1.96 × 0.03842

= **0.0753**

Margin of Error = **7.53 percentage points**

Confidence interval:

Lower bound = 18% - 7.53% = **10.47%**

Upper bound = 18% + 7.53% = **25.53%**

### Final Result
**95% Confidence Interval = 10.47% to 25.53%**

This means the estimated true credential submission rate for Campaign A is approximately 10.47%–25.53%, assuming the sample is representative.
