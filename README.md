# 📈 Ultimate Prop Trading Dashboard & Monte Carlo Simulator

A high-performance, interactive Monte Carlo simulation dashboard built for systematic traders. This tool helps visualize the probabilistic outcomes of trading strategies and evaluates the statistical likelihood of passing Prop Firm challenges based on your custom metrics.

## 🎯 Overview

When trading, especially under strict Prop Firm rules (e.g., hard stop drawdowns), knowing your edge isn't enough. You need to understand the variance. This dashboard simulates thousands of equity curves instantly, giving you a realistic picture of your strategy's expected performance, drawdowns, and streaks.
![Trading Dashboard Preview](dashboard-preview.png)
## ✨ Key Features

* **⚡ Lightning Fast Simulations:** Run up to thousands of Monte Carlo simulations instantly right in the browser.
* **⚙️ Dynamic Strategy Config:** Adjust Account Size, Win Rate (%), Risk to Reward (R), and Trade Costs.
* **🛡️ Risk Management Focus:** Set your Hard Stop Drawdown (%) to accurately simulate Prop Firm failure conditions.
* **📊 Advanced Analytics:**
  * Prop Firm Pass Rate (%)
  * Net Expectancy in R
  * Gross Profit Factor
  * Median End Balance
  * Average Win / Loss Streaks
* **📉 Interactive Equity Curve:** Visualizes the Best, Worst (Blown), and Median paths, along with a 95% Confidence Interval.

## 🛠️ Tech Stack

* **HTML5 / CSS3:** Custom sleek Dark Mode UI with premium aesthetic variables.
* **Vanilla JavaScript:** Core Monte Carlo simulation engine and DOM manipulation.
* **Chart.js:** High-performance rendering for the equity curve graph.

## 🚀 How to Use

Since this is a client-side web application, no installation or server is required!

1. Download or clone the repository.
2. Open the `index.html` (or `trading_dashboard.html`) file directly in any modern web browser.
3. Tweak the sliders on the left panel to match your trading strategy.
4. Click **Run Simulation** and analyze your stats!

---
*Created by [@ItsD1m](https://github.com/ItsD1m)*
