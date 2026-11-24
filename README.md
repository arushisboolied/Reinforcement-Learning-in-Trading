# 📈 RL in Trading
### Teaching Machines to Beat the Market 🤖

Ever wondered if you could teach a computer to trade stocks?

Instead of hardcoding trading strategies, what if we let an agent learn from its mistakes, experiment with different decisions, and gradually figure out when to **Buy, Sell, or Hold**?

Welcome to **RL in Trading** — a hands-on exploration of the intersection of Reinforcement Learning, Mathematics, Programming, and Finance.

Over this workshop, we'll go from Python fundamentals and the basics of Reinforcement Learning to building our very own trading agent using **Tabular Q-Learning**.

## 🎯 The End Goal

We'll eventually build an autonomous trading agent that learns to make trading decisions using historical stock market data.

Our agent will:
- Observe market conditions through features derived from historical price data.
- Choose between three actions: **Buy, Sell, or Hold**.
- Receive rewards based on its trading decisions.
- Learn through trial and error using Q-Learning.
- Be evaluated on unseen market data and compared against a simple Buy-and-Hold strategy.

Will our agent outperform simply buying a stock and holding onto it? Let's find out!

## 🗺️ The Roadmap

The workshop is divided into four modules, each building upon the previous one.

### Week 1 — Getting Our Hands Dirty with Python 🐍

Getting comfortable with the tools we'll use throughout the workshop.

- Python fundamentals
- NumPy for numerical computing
- Pandas for data manipulation
- Matplotlib for data visualisation

📂 **[Explore Week 1](./week1/)**

### Week 2 — Teaching Machines to Learn 🧠

An introduction to Reinforcement Learning and sequential decision-making.

- RL fundamentals: agents, environments, states, actions and rewards
- Exploration vs exploitation
- Multi-Armed Bandit Problem
- ε-greedy and Upper Confidence Bound (UCB)
- Implementing and experimenting with bandit algorithms

📂 **[Explore Week 2](./week2/)**

### Week 3 — From Slot Machines to Stock Markets 💹

Bridging the gap between theoretical RL and financial applications.

- Introduction to financial markets and historical price data
- Working with `yfinance`
- Returns, volatility and technical indicators
- Markov Decision Processes
- Formulating trading problems as RL environments

📂 **[Explore Week 3](./week3/)**

### Week 4 — Building Our Very Own Trading Agent 🚀

Putting everything together to build and evaluate a trading agent.

- Creating a custom trading environment
- Implementing Tabular Q-Learning
- Training an agent with Buy, Sell and Hold actions
- Backtesting on historical data
- Evaluating on unseen data
- Comparing against a Buy-and-Hold baseline

📂 **[Explore Week 4](./week4/)**

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| NumPy | Numerical computations |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualisation |
| yfinance | Historical stock market data |
| Jupyter Notebook | Interactive experimentation |

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/arushisboolied/Reinforcement-Learning-in-Trading.git
cd Reinforcement-Learning-in-Trading
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**macOS / Linux**
```bash
source .venv/bin/activate
```

**Windows**
```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start exploring!

Each week's directory contains its corresponding learning material, notebooks and exercises.

Start with Week 1 and work your way through the modules!

## 📊 The Final Showdown

At the end of the workshop, we'll put our agent to the test against a Buy-and-Hold strategy.

We'll explore metrics such as:

- **Cumulative Returns:** How much did our portfolio grow?
- **Sharpe Ratio:** How good were the returns relative to the risk taken?
- **Maximum Drawdown:** How bad was the worst peak-to-trough decline?
- **Transaction Costs:** How much do trading fees eat into our profits?

The goal isn't just to build an agent that makes money in a simulation, but to understand how well it learns, where it succeeds, and where it fails.

## 📚 Learning Resources

- [Reinforcement Learning: An Introduction — Sutton & Barto](http://incompleteideas.net/book/the-book-2nd.html)
- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [yfinance Documentation](https://ranaroussi.github.io/yfinance/)

## ⚠️ Disclaimer

This is an educational project intended to explore Reinforcement Learning and its applications in financial markets. Historical performance does not guarantee future results, and the trading agent is not intended for real-money trading.

After all, beating the market is a lot harder than beating a classroom example!

---

**Happy Learning, Happy Trading! 📈🤖**
