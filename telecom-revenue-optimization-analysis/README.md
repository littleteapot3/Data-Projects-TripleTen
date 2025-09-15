# Megaline Telecom Revenue Analysis

*Data-driven plan comparison to optimize advertising spend*

## What This Project Does

Megaline, a telecom company, has two mobile plans and a limited advertising budget. They needed to know: **which plan actually makes more money?** 

Using real customer data from 500 subscribers, I analyzed usage patterns and revenue to answer this question with statistical confidence.

**The bottom line**: Ultimate plan customers generate 23% more revenue ($72 vs $58 monthly average), and the difference is statistically significant.

---

## The Business Problem

Megaline offers two prepaid plans:
- **Surf**: $20/month with basic allowances 
- **Ultimate**: $70/month with generous limits

The marketing team needed to know where to spend their budget. My job was to dig into the data and find out which plan drives more revenue per customer.

## What I Found

**Revenue Winner**: Ultimate plan users pay significantly more each month
- Ultimate: $72.17 average monthly revenue
- Surf: $58.53 average monthly revenue  
- Difference: $13.64 per customer (23% higher)

**Usage Patterns**: Ultimate customers actually use what they pay for
- Send 35% more text messages
- Use 18% more data
- Same call patterns as Surf users

**Hidden Opportunity**: 534 Surf customers regularly exceed their limits - prime candidates for plan upgrades

## The Analysis

I worked with five datasets covering calls, texts, internet usage, customer info, and plan details. After cleaning the data and applying Megaline's billing rules (like rounding up call minutes), I calculated accurate monthly revenue for each customer.

**Statistical Testing**: Used Welch's t-test to confirm the revenue difference is real, not just random chance (p < 0.001, large effect size).

**Business Rules Applied**: 
- Call durations rounded up to nearest minute
- Data usage rounded up to nearest GB per month
- Proper overage calculations for each plan

## Key Tools Used

- **Python** for data processing and analysis
- **Pandas** for data manipulation  
- **Scipy** for statistical testing
- **Matplotlib/Seaborn** for visualizations
- **Jupyter** for reproducible analysis

## Repository Structure

```
megaline-telecom-analysis/
├── megaline-profitability-analysis.ipynb    # Main analysis
├── data/                                     # CSV datasets
├── README.md                                # This file
└── requirements.txt                         # Python dependencies
```

## Business Recommendations

1. **Focus ad spend on Ultimate plan** - higher revenue per customer with statistical backing
2. **Target high-usage Surf customers** - 534 users already paying over $30/month 
3. **Consider introducing a middle tier** - bridge the gap between $20 and $70 plans

**Potential Impact**: Converting just the high-usage Surf customers could generate an additional $87K annually.

## What Makes This Analysis Reliable

- **Proper statistical testing** with effect size calculations
- **Business rule validation** ensuring accurate revenue calculations  
- **Comprehensive data cleaning** with clear documentation of decisions
- **Real-world applicability** with concrete business recommendations

## Running the Analysis

```bash
# Clone the repository
git clone https://github.com/yourusername/megaline-revenue-analysis.git

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter lab megaline-profitability-analysis.ipynb
```

The analysis takes about 5 minutes to run and includes validation checks to ensure calculations are correct.

---

*This project demonstrates statistical analysis, business intelligence, and data-driven decision making for revenue optimization.*
