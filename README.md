# GRAND THIEF CASH

# Background

# Knowledge Base

## Economics
### Micro Economics
MIT1401 Micro Economic [LINK](https://www.bilibili.com/video/BV1oo4y1o7nZ/?spm_id_from=333.337.search-card.all.click&vd_source=7880edeb390f6ef3f8bdd4ce778050f3)

## Stragegies Learn
- 你见过哪些耳目一新的量化交易策略？ - 量化QuantBoy的回答 - 知乎
https://www.zhihu.com/question/264155185/answer/3104262214
- 基于套利定价理论的七因子策略
https://mp.weixin.qq.com/s/HpRKPW6bGNTXoCXmZdK8ow
- 

# Team & Coop

## Understand Azure Devops
Understand Azure Devops [Click Here](https://learn.microsoft.com/en-us/azure/devops/boards/backlogs/define-features-epics?view=azure-devops&tabs=agile-process)

Azure Devops [Link](https://dev.azure.com/grand-thief-cash/data-fetcher/_workitems/recentlycreated/)

# Development

## Architecture
![architecture](/images/architecture.jpg "Architecture Diagram")

## Module Explanation
###  Data Acquisition and Processing Module

#### Purpose
The Data Acquisition and Processing Module aims to collect, clean, transform, and store financial market data for quantitative trading strategies. Its primary role is to ensure high-quality data availability for trading decisions.

#### Significance
This module is pivotal in quantitative trading, as data quality directly affects strategy effectiveness. Proper data management allows for pattern recognition and market opportunity identification.

#### Components
- **Data Sources**: Interfaces with stock exchanges, data providers, and financial databases to gather raw market data.
- **Data Cleaning**: Rectifies errors, inconsistencies, and missing data to ensure integrity.
- **Data Transformation**: Converts raw data into usable formats, aggregating or calculating derived indicators.
- **Data Storage**: Archives processed data in databases or data structures for retrieval.
- **Data Update**: Ensures continual synchronization with real-time market conditions.

### Signal Generation Module

In a quantitative trading system, the **Signal Generation Module** plays a pivotal role in identifying trading opportunities by generating trading signals. This module serves the primary purpose of translating market data into actionable signals, helping traders or algorithms make informed buy or sell decisions. The significance of the Signal Generation Module lies in its ability to systematically analyze data, apply predefined strategies, and provide clear directives for executing trades.

#### Components of Signal Generation Module
- **Data Ingestion**: This component is responsible for collecting and processing market data from various sources such as price feeds, news, and economic indicators. It includes data cleaning, normalization, and transformation processes to ensure data consistency.
- **Feature Engineering**: Feature engineering involves creating relevant variables or features from raw data to enhance signal generation accuracy. These features can include moving averages, volatility measures, technical indicators, and more.
- **Strategy Formulation**: Traders or algorithm developers define trading strategies based on their analysis and market hypotheses. Strategies can be trend-following, mean-reversion, arbitrage, or any other rule-based approach. This component encapsulates these strategies into executable code.
- **Signal Generation Logic**: This is the core of the module, where strategies are implemented to generate trading signals. Depending on the chosen strategy, signals may be generated when specific conditions or criteria are met, such as crossovers of moving averages or price reaching a certain threshold.
- **Risk Management**: A critical aspect of signal generation is risk management. This component ensures that trading signals are generated with risk considerations in mind, such as position sizing, stop-loss orders, and risk limits.
- **Backtesting**: Before deploying signals in live trading, they are rigorously tested using historical data. Backtesting assesses the performance of the signals under different market conditions, helping fine-tune strategies and identify potential flaws.


## Useful Links
### Open Source quant relevant repositories summary:
- ai_quant_trade [link](https://github.com/charliedream1/ai_quant_trade)
- awesome-quant [link](https://github.com/thuquant/awesome-quant)

### Tutorial
- Azure Devops [link](https://learn.microsoft.com/en-us/azure/devops/organizations/settings/work/change-process-basic-to-agile?view=azure-devops)

### Project Management
- Azure Devops [link](https://dev.azure.com/grand-thief-cash/data-fetcher/_workitems/recentlycreated/)