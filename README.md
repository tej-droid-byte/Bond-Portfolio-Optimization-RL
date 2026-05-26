# 📈 Bond Market Portfolio Optimization using Reinforcement Learning & Power BI

![Python](https://img.shields.io/badge/Python-3.x-yellow)
![RL](https://img.shields.io/badge/Reinforcement-Learning-green)
![DQN](https://img.shields.io/badge/DQN-Agent-blue)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-orange)
![Finance](https://img.shields.io/badge/Finance-Portfolio%20Optimization-red)

<p align="center">
  <img src="screenshots/Bond%20Market%20Portfolio%20Optimization%20Dashboard%20Overview.png" width="900">
</p>

Reinforcement learning–based bond portfolio optimization project leveraging Deep Q-Networks (DQN) for trading strategy development and interactive Power BI dashboards for portfolio analytics and agent behavior visualization.

The project simulates Buy–Sell–Hold decisions within a bond portfolio environment and evaluates portfolio evolution using cumulative rewards and trading behavior analysis.

---

# 📌 Project Description

This project focuses on optimizing bond portfolio decisions using Reinforcement Learning.

A Deep Q-Network (DQN) agent was trained to interact with a portfolio environment and learn optimal trading actions:

- Buy
- Sell
- Hold

The objective was to maximize cumulative rewards while learning effective portfolio management strategies dynamically from environment feedback.

The Power BI dashboard enables exploration of:

- Portfolio performance evolution
- Reward progression
- Trading decisions
- Agent behavior distribution
- Reinforcement learning outcomes

---

# ⚙️ Methodology / Workflow

## 1. Environment & Data Preparation

Bond market observations and portfolio state information were prepared for RL training.

Inputs included:

- Portfolio state representation
- Trading actions
- Reward signals
- Environment observations

Preprocessing steps:

- State generation
- Reward formulation
- Episode creation
- Environment simulation

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
Buy / Sell / Hold Action
            ↓
Reward Calculation
            ↓
Portfolio Update
```

The agent continuously improved its policy using reward feedback from the environment.

---

## 3. Power BI Dashboard Development

Interactive dashboards were developed to visualize reinforcement learning outcomes.

Dashboard Components:

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

![Dashboard](screenshots/Bond%20Market%20Portfolio%20Optimization%20Dashboard%20Overview.png)

---

# 🛠 Tech Stack

## Reinforcement Learning & AI

- Python
- Deep Q-Network (DQN)
- Reinforcement Learning
- NumPy
- Pandas

## Visualization & Analytics

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
│   └── Bond Market Portfolio Optimization Dashboard Overview.png
│
├── README.md
└── .gitignore
```

---

# 📈 Results

The DQN agent demonstrated learning behavior through sequential interactions and achieved positive cumulative reward progression.

Power BI dashboards enabled interactive analysis of:

- Portfolio evolution
- Reward behavior
- Trading actions
- Decision distributions
- Reinforcement learning performance

---

# 📌 Project Highlights

- Reinforcement Learning portfolio optimization
- Deep Q-Network implementation
- Financial analytics dashboard
- Trading strategy analysis
- Power BI integration
- Interactive RL visualization

---

# 🚀 Future Enhancements

- PPO / A2C implementation
- Multi-asset portfolio optimization
- Risk-adjusted reward formulation
- Real-time market integration
- Deployment as analytics platform

---

# 👨‍💻 Author

**Tej More**  
MS Data Science — Rochester Institute of Technology  
AI • Reinforcement Learning • Finance • Healthcare AI
