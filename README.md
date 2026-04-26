# NYC Market Intelligence: Airbnb Pricing and Strategy Analysis

## Project Overview
This project provides a data-driven deep dive into 30,000+ Airbnb listings in New York City. The primary objective was to move beyond basic descriptive statistics and identify the statistically significant drivers of pricing to assist prospective hosts in optimizing their market entry strategy.

## Key Business Insights
Contrary to common market assumptions, this analysis revealed several non-obvious trends regarding revenue optimization:

* **The Privacy Premium:** Entire Home listings command a price premium of approximately 2x over private rooms. This factor remains the most significant predictor of price regardless of host experience or neighborhood popularity.
* **Location Dominance:** Manhattan remains the primary price driver, outperforming other boroughs by a significant margin across all accommodation types.
* **The Experience Myth:** Statistical testing showed that Host Tenure (seniority) has a near-zero correlation with pricing. This suggests that new market entrants can compete effectively if they prioritize property type and location over personal branding.
* **Diminishing Returns on Bed Count:** Data indicates that increased bed counts do not linearly scale with price, suggesting a "sweet spot" for 1-2 bedroom high-privacy listings in high-demand zones.

## Tech Stack and Methodology
* **Analysis:** Python (Pandas, NumPy)
* **Visualization:** Seaborn, Matplotlib
* **Techniques:** Exploratory Data Analysis (EDA), Statistical Hypothesis Testing, Data Cleaning, and Feature Binning.

## Project Structure
* **NYC_Airbnb_Pricing_Analysis.ipynb:** Full technical workflow including data ingestion, cleaning, and multivariate visualization.
* **Executive_Summary_Airbnb_NYC.pdf:** A high-level professional report detailing the findings and strategic recommendations.
* **data/:** Directory containing the source dataset (or link to original source).

## Methodology Summary
The analysis was conducted through a multi-stage pipeline:
1. **Data Cleaning:** Handling missing host data and correcting inconsistent review score bins.
2. **Univariate Analysis:** Establishing baseline distributions for price, bed counts, and host tenure.
3. **Bivariate/Multivariate Analysis:** Testing correlations between location, room types, and price.
4. **Hypothesis Validation:** Using box plots and distribution charts to confirm or disconfirm market assumptions.

---
