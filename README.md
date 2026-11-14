# Hydropower-Commercial-Intelligence

**Business Intelligence proof of concept for commercial decision-making in the hydropower industry, built with Power BI and simulated data.**

## Project Overview

This project explores how Business Intelligence can support commercial decision-making in the hydropower industry.

The dashboard was developed as a practical extension of research on how BI can improve commercial performance through:

- Bid / No-Bid decision support
- Pricing discipline and risk monitoring
- Market targeting and portfolio prioritization

The objective is not to automate managerial decisions, but to make them more **structured, transparent, consistent and data-driven**.

## Business Questions

The proof of concept addresses three main questions:

1. **Which commercial opportunities should be prioritized?**
2. **How can pricing, margin and execution risk be monitored more effectively?**
3. **Which markets should receive greater commercial attention?**

## Dataset

The dashboard uses a **fully simulated portfolio of 24 hydropower commercial opportunities** created for demonstration purposes.

No confidential or proprietary company data is included in this repository.

## Dashboard Structure

The Power BI dashboard contains four pages:

### 1. Executive Overview

Provides a high-level view of the commercial portfolio through key indicators such as:

- Pipeline value
- Weighted pipeline value
- Expected margin
- Opportunity distribution
- Strategic priority
- Risk exposure

### 2. Bid / No-Bid & Opportunity Scoring

Supports opportunity selection through a weighted scoring model.

The Opportunity Score combines:

| Criterion | Weight |
|---|---:|
| Strategic Fit | 20% |
| Expected Margin | 20% |
| Technical Feasibility | 15% |
| Client Attractiveness | 15% |
| Execution Risk | 15% |
| Competitive Position | 10% |
| Data Confidence | 5% |

Opportunities are then classified as:

- **Prioritize:** Score ≥ 4.0
- **Review:** Score ≥ 3.0 and < 4.0
- **Do Not Prioritize:** Score < 3.0

The weights and thresholds are illustrative and are intended to demonstrate the decision-support mechanism rather than represent an industry-standard scoring model.

### 3. Pricing & Risk

Provides visibility into:

- Expected margin
- Cost uncertainty
- Commercial risk
- Execution risk
- Pricing discipline

The objective is to help identify opportunities where attractive revenue potential may be offset by margin pressure or execution uncertainty.

### 4. Market Targeting & Portfolio Prioritization

Combines opportunity-level performance with market attractiveness.

The Market Attractiveness Score considers:

| Criterion | Weight |
|---|---:|
| Market Potential | 20% |
| Installed Base | 15% |
| Modernization Potential | 20% |
| Project Pipeline | 20% |
| Competitive Intensity | 10% |
| Regulatory Environment | 15% |

Portfolio priority is based on the combination of the **Opportunity Score** and **Market Attractiveness Score**:

`Combined Score = (Opportunity Score + Market Attractiveness Score) / 2`

Priority levels:

- **High:** Combined Score ≥ 4.0
- **Medium:** Combined Score ≥ 3.0 and < 4.0
- **Low:** Combined Score < 3.0

This approach reflects the idea that an attractive market alone is not sufficient: the quality of the individual commercial opportunity also matters.
## Dashboard Screeshots

## Key Features

- Interactive Power BI dashboard
- Commercial opportunity scoring
- Bid / No-Bid decision support
- Pricing and margin analysis
- Risk monitoring
- Market attractiveness assessment
- Portfolio prioritization
- Executive KPI reporting

## Tools

- **Power BI**
- **Power Query**
- **DAX**
- **Excel**

## Key Takeaway

The project demonstrates how Business Intelligence can move beyond descriptive reporting and support more structured commercial decision-making.

Rather than replacing managerial judgment, BI can provide a common analytical framework for comparing opportunities, identifying risk, allocating commercial resources and prioritizing markets.

## Disclaimer

This project is a proof of concept created for academic and portfolio purposes.

All commercial opportunities, financial values, scoring criteria, weights and thresholds are simulated or illustrative and should not be interpreted as representing any specific company's commercial strategy or decision-making process.
