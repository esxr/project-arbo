Here is a consolidated list of key **concepts** used across the various papers related to statistical arbitrage, reinforcement learning, and arbitrage strategies in different markets:

---

### **Statistical Arbitrage Concepts**:
1. **[[Mean Reversion]]**: The concept that asset prices tend to revert to their long-term mean over time.
2. **[[Cointegration]]**: A statistical property where two or more time series exhibit a long-term equilibrium relationship despite being individually non-stationary.
3. **[[Partial Cointegration]]**: A relaxation of the strict cointegration assumption, where the residuals may have both a mean-reverting component and a random walk.
4. **[[Pairs Trading]]**: A market-neutral strategy involving long and short positions in two correlated assets to profit from mean reversion.
5. **[[Spread Trading]]**: Trading based on the price difference between two assets, often used in pairs trading.
6. **[[Hurst Index]]**: A measure of the long-term memory of a time series, used to identify whether the spread is mean-reverting or persistent.
7. **[[Ornstein-Uhlenbeck Process]]**: A stochastic process used to model mean-reverting behavior in financial markets.
8. **[[Kalman Filter]]**: A recursive algorithm for estimating the dynamic state of a system, often used for time-varying spread estimation in statistical arbitrage.

---

### **Reinforcement Learning (RL) Concepts**:
1. **[[Reinforcement Learning (RL)]]**: A machine learning framework where an agent learns to take actions in an environment to maximize cumulative rewards.
2. **[[Asynchronous Advantage Actor-Critic (A3C)]]**: A deep RL algorithm where multiple agents work asynchronously to optimize policy and value functions.
3. **[[Advantage Actor-Critic (A2C)]]**: A synchronous version of A3C where the agent learns an optimal trading policy using both value and policy gradients.
4. **[[Reward Function]]**: The function that assigns a numerical reward based on the agent’s actions, designed to encourage profitable and risk-averse trading behavior.
5. **[[State Space]]**: The set of variables (e.g., asset prices, spreads, volatility) that the agent uses to make decisions in reinforcement learning.
6. **[[Action Space]]**: The set of possible actions (e.g., buy, sell, hold) the agent can take at any given time.
7. **[[Exploration-Exploitation Tradeoff]]**: A concept in RL where the agent balances exploring new strategies and exploiting known profitable strategies.
8. **[[Empirical Mean Reversion Time]]**: A metric used to quantify how quickly a spread between two assets returns to its historical mean.
9. **[[Behavior Cloning]]**: A method in RL where the agent mimics expert actions during initial training phases to guide learning.

---

### **Machine Learning and Deep Learning Concepts**:
1. **[[Convolutional Neural Networks (CNNs)]]**: A type of deep learning model designed to capture patterns in time-series data.
2. **[[Transformers]]**: Deep learning models with self-attention mechanisms used to capture long-term dependencies in time series.
3. **[[Autoencoders]]**: Neural networks used to learn efficient representations of data, often for dimensionality reduction or data augmentation.
4. **[[Generative Adversarial Networks (GANs)]]**: A framework where two neural networks (generator and discriminator) compete to generate realistic synthetic data.
5. **[[Wasserstein GAN (WGAN)]]**: A type of GAN that uses a Wasserstein distance measure to improve training stability.
6. **[[Data Augmentation]]**: Techniques such as GANs and autoencoders used to artificially expand training data, particularly for improving model robustness.
7. **[[Technical Indicators]]**: Derived indicators such as moving averages, Bollinger bands, and RSI used in price forecasting models.

---

### **Market and Financial Trading Concepts**:
1. **[[Price Arbitrage]]**: Profiting from price differences of the same asset across different markets or time periods (e.g., day-ahead vs. intraday markets).
2. **[[Limit Order Book (LOB)]]**: The record of buy and sell orders in a market, showing available volumes at different price levels.
3. **[[Smart Order Routing (SOR)]]**: An algorithm used to optimize trade execution by routing orders across multiple venues to minimize costs and maximize execution speed.
4. **[[Intraday Markets]]**: Electricity markets where trading occurs within the day of delivery, typically used to balance supply and demand.
5. **[[Balancing Market]]**: Real-time markets where imbalances in supply and demand are settled during the delivery period.
6. **[[Day-Ahead Market (DAM)]]**: Auction-based markets where electricity is traded a day before actual delivery.
7. **[[Continuous Intraday Market (CID)]]**: Markets where electricity can be traded continuously up to one hour before delivery.

---

### **Risk Management and Performance Metrics**:
1. **[[Sharpe Ratio]]**: A measure of risk-adjusted return, calculated as the average return per unit of risk (volatility).
2. **[[Maximum Drawdown]]**: The maximum observed loss from a peak to a trough in a portfolio’s value.
3. **[[Calmar Ratio]]**: A performance metric that compares the average annual return to the maximum drawdown.
4. **[[Value-at-Risk (VaR)]]**: A risk metric used to estimate the potential loss in a portfolio over a given time period with a certain confidence level.
5. **[[Stop-Loss Mechanisms]]**: Automated rules that exit positions when losses exceed a predefined threshold to prevent further losses.

---

Let me know if you need further adjustments!