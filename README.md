# 📈 Bond Market Portfolio Optimization using Reinforcement Learning & Power BI

![Python](https://img.shields.io/badge/Python-3.x-yellow)
![RL](https://img.shields.io/badge/Reinforcement-Learning-green)
![DQN](https://img.shields.io/badge/DQN-Agent-blue)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-orange)
![Finance](https://img.shields.io/badge/Finance-Portfolio%20Optimization-red)

<p align="center">
  <img src="screenshots/Bond RL Dashboard.png" width="900">
</p>

Reinforcement learning–based bond portfolio optimization project leveraging Deep Q-Networks (DQN) for trading strategy development and Power BI dashboards for portfolio analytics and decision visualization.

The project simulates portfolio decisions using Buy–Sell–Hold actions and evaluates agent performance using cumulative reward trends and portfolio behavior analysis.

---

# 📌 Project Description

This project focuses on portfolio optimization in bond markets using Reinforcement Learning.

A DQN agent was trained to learn optimal trading behavior by interacting with a financial environment and selecting actions:

- Buy
- Sell
- Hold

The objective was to maximize portfolio performance and cumulative rewards while learning trading behavior dynamically from market states.

Power BI dashboards were developed to analyze:

- Portfolio performance
- Reward progression
- Trading decisions
- Agent behavior distribution
- Reinforcement learning outcomes

---

# ⚙️ Methodology / Workflow

## 1. Data Preparation

Bond market information and portfolio state variables were prepared for RL training.

Input features included:

- Portfolio state representation
- Market observations
- Trading decisions
- Reward signals

Preprocessing included:

- State generation
- Environment construction
- Reward formulation
- Sequential episode setup

---

## 2. Reinforcement Learning Agent Development

A Deep Q-Network (DQN) agent was implemented for portfolio optimization.

Pipeline:

```text
Bond Market Environment
            ↓
State Observation
            ↓
DQN Agent
            ↓
Buy / Sell / Hold Decision
            ↓
Reward Calculation
            ↓
Portfolio Update
```

The agent continuously learned through environment interaction and reward feedback.

---

## 3. Power BI Dashboard Development

Interactive dashboards were created for reinforcement learning performance analysis.

Dashboard components include:

✅ Portfolio Performance Trend

✅ Reward Evolution During Training

✅ Agent Decision Distribution

✅ Trading Actions Across Episodes

✅ KPI Monitoring:

- Final Cumulative Reward
- Total Reward
- Average Reward
- Total Decisions

---

# 📊 Dashboard Preview

![Dashboard](screenshots/Bond RL Dashboard.png)

---

# 🛠 Tech Stack

## Reinforcement Learning & AI

- Python
- Deep Q-Network (DQN)
- Reinforcement Learning
- NumPy
- Pandas

## Analytics & Visualization

- Power BI
- DAX
- Portfolio Analytics

## Development Tools

- Jupyter Notebook
- Git
- GitHub

---

# 📂 Repository Structure

```text
Bond-Portfolio-Optimization-RL/
│
├── dashboard/
│   └── Bond_RL_Dashboard.pbix
│
├── data/
│   └── bond_rl_powerbi.csv
│
├── notebooks/
│   └── bond_portfolio_rl.ipynb
│
├── screenshots/
│   └── Bond RL Dashboard.png
│
├── README.md
└── .gitignore
```

---

# 📈 Results

The DQN agent learned portfolio behavior through sequential interactions and demonstrated positive cumulative reward progression.

Power BI dashboards enabled interactive exploration of:

- Reward trends
- Trading behavior
- Action distributions
- Portfolio performance evolution

---

# 📌 Project Highlights

- Reinforcement Learning portfolio optimization
- Deep Q-Network implementation
- Trading strategy analysis
- Financial analytics dashboard
- Power BI integration
- Interactive RL visualization

---

# 🚀 Future Enhancements

- PPO / A2C implementation
- Multi-asset portfolio optimization
- Real-time market integration
- Risk-adjusted reward formulation
- Deployment as analytics application

---

# 👨‍💻 Author

**Tej More**  
MS Data Science — Rochester Institute of Technology  
AI • Reinforcement Learning • Finance • Healthcare AI
