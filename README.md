📈 HSI Global Market Cashflow Tracker (恆生指數 - 全球市場資金流追蹤器)
Real-time HSI Algorithmic Dashboard with Global Cash Flow & Inter-Market Correlation.
A professional, single-file quantitative tool for monitoring market impacts in real-time.
 ( New version updated @ 08/02/2026 fixed world map/timestamp issue aligning with HK Market)

🚀 Core Overview
This standalone Python dashboard analyzes the Hang Seng Index (HSI) against 8 major global markets. Built for speed and clarity, it uses a custom impact algorithm to quantify how global volatility shapes HSI movement.
Tech Stack: Python 3.10+ | Dash (Plotly) | Yahoo Finance API
Target: Educational algorithmic trading & market correlation analysis.

✨ Key Features
Real-Time HSI Engine: 10-second updates with clean price/volume data (HKT calibrated).
Global Impact Algorithm: Calculates "HSI Impact Values" using historical correlation coefficients.
Smart Visualization: Color-coded bull/bear trends and dynamic scaling intraday charts.
Zero-Bug Architecture: Fixed zero-volume issues, deprecated Dash APIs, and timezone offsets.
Interactive UI: Dark-mode responsive design with clickable constituent stock lists.

🧮 The Algorithm
The program quantifies global market influence using a weighted correlation formula:
python
HSI Impact = Market Price Change % × Correlation Coefficient × 0.01

Market	Correlation	Market	Correlation
China (SSE)	0.85 (Strongest)	UK (FTSE)	0.65
Japan (Nikkei)	0.78	Germany (DAX)	0.63
USA (S&P 500)	0.72	Australia (ASX)	0.58

🛠️ Installation & Quick Start
Environment: Ensure Python is installed.
Dependencies:
bash
pip install yfinance pandas plotly dash numpy pytz --upgrade

Run:
bash
[python main.py or run hsi-tracker.exe directly](https://github.com/barrykfl-design/hsi-live-tracker-dashboard/blob/main/hsi-tracker.exe)


Access: The dashboard auto-launches at http://127.0.0.1:8050.

📝 Important Notes
Data: Powered by Yahoo Finance (1-2 min delay).
Purpose: Educational use only. Not intended for live financial advice.
License: MIT License — Free for personal and commercial use.
Developed for traders and students exploring algorithmic market logic.



