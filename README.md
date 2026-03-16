# IPO_Analysis

## Project goal
The main goal of this project is to develop a ranking system that predicts the investment risks of investing in IPO companies on the American stock market, based on data for the last five years (2019-2024), as well as identifying and analyzing the critical factors that determine the degree of investment risk. Next, we need to analyze whether this system can be applied to the emerging Russian stock market.

## Subject of research
The subject of the study is the process of investment risk assessment in initial public offerings (IPOs) of startups.  This research analyzes classical valuation approaches (such as P/S, DCF, etc.) and compares them with a new ranking system, also developed using data set analysis and machine learning, in order to identify hidden patterns that predict high-risk IPOs.

## Object of research
The object of the study is startups going public with data obtained from public sources (stockanalysis.com) on the US stock market for comparative analysis with the Russian stock market. The objects under study include companies from different sectors of the stock market showing different indicators of success and failure after going public, which should make it possible to form a representative sample for building a system of investment risk ranking.

## Expected results
*Developed ranking system*: Creation of a system combining classical methods and methods of data analysis after comparative analysis of each separately. This system should allow investors and venture funds to more accurately assess the potential risks of equity offerings, minimize the probability of unprofitable investments, and make more informed decisions.

*Research Report*: Preparation of a detailed analytical report that substantiates the methodology, research stages, comparative analysis results and recommendations that will facilitate decision-making for management companies and investors.

*Visualization of results*: Development of an interactive dashboard in Power BI, allowing to visually demonstrate the results of the ranking system and risk forecasts, as well as displaying the sectors of the stock market in which the ranking system identifies the most unstable IPO sector.  


## Data description
Over the last five years, more than 2,000 Initial Public Offerings have taken place in the U.S. stock market, indicating a high level of activity in the primary capital market during this period. In order to obtain structured and complete data on all IPOs in the U.S., it is required to get paid access to a professional database, for example, on the StockAnalysis.com, which provides information on IPO dates, company characteristics, offering prices, amounts of capital raised and other relevant information.

There are such columns in the dataset : 'IPO Date', 'Symbol', 'Company Name', 'IPO Price', 'Return', 'Market Cap', 'Shares Offered', 'Deal Size', 'Open Price', 'Return (Open)', 'Exchange', 'Is SPAC', 'Sector', 'Industry', 'Country', 'Employees', 'Volume', 'Rel. Volume', 'Close', '% Change', 'Premkt. Price', 'Premkt. Chg', 'Premkt. Chg%', 'Ent. Value', 'PE Ratio', 'Forward PE', 'PS Ratio', 'PB Ratio', 'P/FCF', 'ROE', 'ROA', 'ROIC', 'Rating', 'Analysts', 'Price Target', 'PT Upside (%)', 'Div. ($)', 'Div. Yield', 'Div. Growth', 'Payout Freq.', 'Payout Ratio', etc.

The analyzed dataset includes 75 variables describing both the characteristics of companies going public and their financial and market indicators before and after the offering. The data structure covers a wide range of attributes, from basic company identifiers (IPO date, ticker, name) to fundamental multiples (P/E, P/S, P/B), profitability (ROE, ROA, ROIC), market capitalization, trading volume, yield, dividend policy, and industry affiliation.
In addition, the dataset includes variables reflecting stock behavior on the offering day and subsequent periods (e.g., opening yield, pre-market volume, price change), as well as the presence of attributes such as institutional investor participation. This variety of attributes makes the dataset suitable for building investment risk assessment models and predicting IPO success using machine learning methods.
