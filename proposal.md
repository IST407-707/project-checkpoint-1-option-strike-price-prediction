# Proposal for Estimating True Value of Strike Prices Using Machine Learning

### Title
**ML-Driven Estimation of Strike Price Valuation in Options Trading**

### Team
- Pranav Mahesh Mekal (point of contact)
- Shaik Mohammed Nawazish Khalander (Naz)


### Introduction
We aim to develop a machine learning model that accurately estimates the "subjectively true" value of strike prices in options trading by analyzing market data, financial indicators, and global economic factors. Our approach is novel because it combines advanced machine learning techniques with an extensive dataset, including implied volatility and macroeconomic indicators, to predict strike price valuation more accurately than current market mechanisms. This project matters because it has the potential to revolutionize options trading strategies by identifying mispriced options, offering significant opportunities for arbitrage and strategic investment, thereby enhancing market efficiency.

- **What are we trying to do?** We're developing a machine learning model to estimate the true value of strike prices in options trading more accurately than the current market mechanisms.
- **What is new in our approach and why do we think it will be successful?** Our approach is differnt because it integrates diverse datasets with advanced machine learning algorithms, focusing on features that are traditionally overlooked in standard valuation methods. This comprehensive model promises improved accuracy in estimating strike prices. We exclude certain trading days/timse while training the model because of extreme volatility, this comes from personal experience dealing with the Indian stock market which should be similar to the NYSE/NASDAQ.
- **Who cares?** Traders, financial institutions, and market analysts( hopefully us as well) will greatly benefit from our model. Success in our project means providing these stakeholders with a tool for identifying undervalued or overvalued options, thus paving the way for more informed and strategic trading decisions.

### Literature Review
Current practices in options trading rely heavily on models like Black-Scholes and binomial trees, which often overlook the impact of sudden market movements and macroeconomic factors. Recent studies have begun exploring machine learning in financial markets, yet few have specifically targeted the accurate valuation of options strike prices through such an integrated and comprehensive approach.

- **How is it done today, and what are the limits of current practice?** Today's methods depend on traditional financial models that may not account for all variables affecting an option's price, leading to potential mispricing.
- **Stakeholders and Needs:**
  - **Traders:** Need accurate, real-time valuations to make informed decisions.
  - **Financial Institutions:** Require robust models to manage risk and optimize portfolios.
  - **Market Analysts:** Seek deeper insights into market inefficiencies for predictive analyses.

### Data and Methods

#### Data
We will soon be in the process of compiling a dataset that includes historical options prices, market data of associated stocks, and relevant economic indicators. We plan to source data from financial databases and APIs like Bloomberg and Quandl, ensuring reliability through provenance and metadata analysis.

#### Methods
Our modeling approach will involve preprocessing data to normalize inputs and selecting machine learning algorithms likely to perform well with our data type, such as Random Forests, Gradient Boosting Machines, and Neural Networks. We will evaluate our models based on their ability to accurately predict the true strike prices and their performance in real-world trading scenarios.

### Project Plan(Tentative)

| Period        | Activity           | Milestone  |
| ------------- |:-------------:| -----:|
| 3/1 - 3/8    | Data collection, stakeholder analysis, initial data exploration | Data set compiled, stakeholder needs identified |
| 3/8 - 3/18   | Preprocessing, Feature engineering, preliminary model training | Feature set defined, initial models trained |
| 3/19 - 3/26   | Model refinement and validation | Refined models with preliminary validation results |
| 3/27 - 4/3    | Integration into trading strategy, final testing | Trading strategy developed, final model tested |

### Risks
- **Data Quality and Availability:** Inadequate or inaccurate data could undermine model accuracy. We plan to mitigate this by sourcing from multiple reliable databases and performing rigorous data cleaning and validation, but it is still a key risk nonetheless.
- **Model Overfitting:** There's a risk of developing models too complex for practical use. We'll address this by using cross-validation and regularization techniques.
- **Market Volatility:** Unpredictable market events can affect model performance. 