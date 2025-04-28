# Cryptocurrency-Market-Analysis

Project Description:

This project analyzes real-world cryptocurrency data loaded into **Snowflake** from a CSV file. Using **SQL**, we clean, transform, and analyze key metrics such as market cap, trading volume, and price dynamics.

Through various queries, we aim to uncover insights about market structure, investor behavior, and potential trading opportunities.

---

Tools and Technologies"

- **SQL** (Snowflake)
- **Python/Colab** (for data scraping if needed)

---

Data Cleaning:

- Removed `$` and `,` symbols from `current_price`, `market_cap`, `total_volume`.
- Converted text fields to numeric fields using `TO_NUMBER(REPLACE(...))`.
- Created a `CLEANED_CRYPTO` view for efficient querying.

---

Key Analyses:

- Top Cryptos by Market Cap and Volume
- Price to Volume Ratios
- Market Cap Tiers: Mega Cap, Large Cap, Mid Cap, Small Cap
- Ranking Cryptos by Market Dominance
- Cryptos with High Activity but Low Prices
- Average Market Metrics


---

Key Business Insights:

- Bitcoin dominates both price and market cap but others (Ethereum, Tether) dominate liquidity and trading volume.
- Stablecoins provide significant liquidity despite low volatility.
- Several low-cost assets (e.g., XRP, Dogecoin) are heavily traded, suggesting high retail activity.
- A few coins contribute disproportionately to total market cap (Pareto Principle: 80/20).



