# Mutual Fund Investment Plan

This project demonstrates the creation of a mutual fund investment plan using the past performance of the stock market. Mutual funds are investment vehicles that pool money from multiple investors to purchase a diversified portfolio of stocks, bonds, and other securities. The plan is designed by selecting stocks that offer potential long-term growth, and the strategy is managed by professional fund managers.

## Process for Creating the Mutual Fund Plan

### Step 1: Gather Historical Stock Data
To begin, we collected historical stock data such as:
- Closing prices
- Growth trends over time

This data provides a foundation for evaluating the performance of various stocks in the market.

### Step 2: Calculate Key Metrics
The next step involved calculating two important financial metrics:
- **Return on Investment (ROI)**: To measure how well each stock has performed historically.
- **Volatility (Risk)**: To assess the stability of the stock's returns over time.

These metrics help us identify stocks that balance both risk and reward.

### Step 3: Select Stocks for the Mutual Fund
Using the ROI and volatility data, we selected stocks that:
- Offer a **high ROI** for maximum return potential.
- Have **low volatility** to minimize risk exposure.

This ensures a balanced portfolio with a focus on long-term growth.

### Step 4: Calculate Future Value of Investments
We then calculated the future value of monthly investments based on the expected ROI of the selected stocks. Using the formula for compound interest, we modeled the growth of investments over different time periods.

## Investment Results

By investing ₹10,000 per month in the mutual fund plan, the results are as follows:
- **After 1 year**, the accumulated value is around **₹124,000**.
- **After 5 years**, the investment grows to over **₹715,000**.
- **After 10 years**, the investment reaches nearly **₹1.7 million**.

These results highlight the power of consistent investing and compounding returns over time, making this an ideal plan for long-term investors.

## Key Features

- **Stock Selection**: We used historical data and key metrics (ROI, volatility) to choose the best stocks for long-term growth.
- **Investment Projections**: The project calculates how much an investment can grow over time using monthly contributions and compounding.
- **Long-Term Benefits**: Emphasizes the importance of disciplined investing and demonstrates the benefits of compounding over periods of 1, 5, and 10 years.

## Technologies Used

- **Python**
- **Pandas**: For data manipulation and analysis of historical stock data.
- **NumPy**: For mathematical calculations.
- **Matplotlib/Plotly**: For creating visual representations of investment growth over time.

## How to Run the Project

1. **Install the required libraries**:
   ```bash
   pip install pandas numpy matplotlib plotly
