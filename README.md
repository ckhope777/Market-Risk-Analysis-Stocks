![Python](https://img.shields.io/badge/Python-3.9-blue.svg)  
![Jupyter Notebook](https://img.shields.io/badge/Language-Jupyter%20Notebook-orange?logo=jupyter&logoColor=white)

# Market-Risk-Analysis-Stocks
Project conducts Market Risk Analysis on a portfolio of Indian stocks using historical weekly price data over 8 years. By calculating mean returns and standard deviations (volatility), the project evaluates stock performance and riskiness. These insights serve as valuable tools for investors, financial institutions, and stakeholders in making informed decisions related to creditworthiness, investment strategies, and portfolio optimization.

## Workflow & Steps ##

1. **Problem Definition**  
   - Assess market risk using mean returns & volatility.

2. **Data Preparation**  
   - Collected 8 years of weekly stock prices for 5 Indian stocks.  
   - Cleaned & structured the dataset.  

3. **Return Calculation**  
   - Computed **log returns** using:  
     ```python
     df['returns'] = np.log(df['price']).diff()
     ```

4. **Statistical Analysis**  
   - Calculated **mean returns** (expected performance).  
   - Computed **standard deviation** (volatility as risk).  

5. **Visualization**  
   - Compared risk-return profiles using Python & Tableau.  
   - Highlighted stocks on a mean-variance trade-off plot.  

6. **Interpretation**  
   - Positive mean + low volatility → good long-term candidates.  
   - Negative mean or high volatility → high-risk speculative plays.  

7. **Conclusion**  
   - Infosys, Cipla, and HUL offer better risk-adjusted returns.  
   - Vodafone Idea and Dish TV are highly volatile and riskier.  
   - A diversified portfolio balances both growth and stability.

## Final Results ##

- **Average Weekly Returns (8-Year Data):**  
  - **Vodafone Idea**: **-0.0039**  
  - **Dish TV**: **-0.0037**  
  - **Infosys**: **+0.0021**  
  - **Hindustan Unilever (HUL)**: **+0.0023**  
  - **Cipla**: **+0.0025**  

- **Volatility (Standard Deviation of Returns):**  
  - Higher for Vodafone Idea & Dish TV → **riskier investments**    
  - Lower for Hindustan Unilever & Cipla → **more stable investments**  

- **Key Insights:**  
  - Investors face a **risk-return trade-off**.  
  - Stable stocks (HUL, Cipla, Infosys) are defensive choices.   
  - Riskier stocks (Vodafone, Dish TV) may provide speculative opportunities but carry high volatility.  
  - Diversification reduces overall portfolio risk.  

## Tech Stack ##
- **Python** → pandas, NumPy, matplotlib, seaborn.  
- **Jupyter Notebook** → for data analysis and visualization.
