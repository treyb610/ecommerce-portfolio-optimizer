# ecommerce-portfolio-optimizer
Python toolkit for e-commerce portfolio analysis using advanced data science techniques. Features interactive dashboards, customer segmentation, pricing optimization, and automated business intelligence reporting with Plotly visualizations.

# E-commerce Portfolio Analysis

A practical toolkit for analyzing your product portfolio and making better business decisions. Built from real-world e-commerce challenges.

## What This Does

Ever wondered which products are actually making you money? Or if you're pricing things wrong? This project helps answer those questions by analyzing your product data and giving you actionable insights.

**The main questions it helps answer:**
- Which products should I promote more?
- Am I leaving money on the table with my pricing?
- What gaps exist in my market that competitors could exploit?
- Which customers are most valuable to my business?

## How It Works

The analysis happens in three phases:

**Phase 1: Data Setup**
Takes your raw product data and enriches it with calculated metrics like value scores and performance categories.

**Phase 2: Exploration** 
Creates visual dashboards to help you understand your portfolio - what's working, what isn't, and where opportunities exist.

**Phase 3: Strategy**
Generates specific recommendations with financial impact estimates and implementation timelines.

## Getting Started

You'll need Python and a few common data science libraries:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

Then create your data folders:
```bash
mkdir -p data/raw data/processed
```

## Usage

Start with your product data (CSV with columns like price, rating, category, etc.) and work through the notebooks in order:

1. **Data Collection**: Loads and enhances your data
2. **Analysis**: Creates dashboards and identifies patterns  
3. **Strategy**: Generates recommendations and reports

Each notebook builds on the previous one, so run them in sequence.

## What You'll Get

**Portfolio Health Check**
See how your products break down into categories like "Premium Stars" (high price, high rating) vs "Question Marks" (high price, low rating).

**Pricing Opportunities**
Identify products you could price higher without losing customers, plus items that are overpriced for their quality.

**Market Gaps**
Find price-quality combinations you're not covering that competitors might exploit.

**Customer Insights**
Understand which customer segments drive the most value and how to serve them better.

**Financial Impact**
Get specific dollar estimates for potential revenue increases and cost savings.

## Real Example Output

```
PORTFOLIO HEALTH: 72% (Good - mostly healthy products)
IMMEDIATE OPPORTUNITY: $125K from repricing 23 undervalued products
AT-RISK REVENUE: $75K from 8 overpriced products needing attention
EXPANSION POTENTIAL: $200K from entering 15 market gaps
```

## Technologies Used

- **pandas/numpy**: Data processing
- **plotly**: Interactive charts
- **matplotlib/seaborn**: Static visualizations
- **jupyter**: Development environment

## Common Issues

**"DataTable filtering syntax error"**
Fix filter syntax: `performance_category = "Value Champion"` not `{performance_category} = Value Champion`

**"Missing columns"**
Make sure you run Phase 1 data processing first to create all the calculated fields.

## Customization

The analysis functions are modular, so you can easily:
- Add your own business metrics
- Modify categorization thresholds
- Create custom visualizations
- Integrate with your existing tools

## Why This Approach

This isn't just academic analysis - it's built around practical business questions that e-commerce operators actually face. The insights are designed to be actionable with clear next steps and ROI estimates.

The three-phase structure mirrors how real business analysis typically flows: understand your data, explore the patterns, then decide what to do about it.

## Contributing

Found a bug or want to add a feature? Pull requests welcome. Just make sure to:
- Follow existing code style
- Add comments explaining your changes
- Test with sample data first

## License

MIT License - use it however you want.

## Contact

[Trager Bos]  
[trager.bos@temple.edu]  
[https://www.linkedin.com/in/trager-bos/]
