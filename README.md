🚀 MT5 ↔ tastyfx Trading Bot

> Bridge MetaTrader 5 with tastyfx — Fast, Reliable & Fully Automated



<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/Platform-MT5-orange?logo=metatrader" />
  <img src="https://img.shields.io/badge/API-tastyfx-lightgrey?logo=fastapi" />
  <img src="https://img.shields.io/badge/License-MIT-green?logo=open-source-initiative" />
  <img src="https://img.shields.io/badge/Build-Passing-brightgreen?logo=githubactions" />
</p>
---

✨ Overview

This bot acts as a middleware bridge between MetaTrader 5 Expert Advisor (EA) and the tastyfx API.
It enables seamless trade execution, manages symbol mapping differences
(e.g., EURUSD → EUR/USD), handles secure session creation, and ensures reliable API communication.


---

🔥 Features

🔗 MT5 ↔ tastyfx Bridge – connect EA with tastyfx in real-time

⚡ Fast Trade Execution – low-latency order placement

🔒 Secure WebSocket Sessions – auto-reconnect & keep-alive

🗺️ Symbol Mapping – converts EURUSD → EUR/USD automatically

🧩 Modular Code – easy to extend & maintain

💻 Cross-Platform – supports Windows, Linux, macOS



---

🏗️ Architecture

flowchart LR
    A[MetaTrader 5 EA] --> B[HTTP Requests]
    B --> C[Python Middleware Bot]
    C --> D[WebSocket Session]
    D --> E[tastyfx API]


---

⚙️ Installation

# Clone this repository
git clone https://github.com/KamranAliOfficial/mt5-tastyfx-bridge.git

# Navigate into project folder
cd mt5-tastyfx-bridge

# Install required dependencies
pip install -r requirements.txt


---

🚀 Usage

# Run the bot
python bot.py

1. Configure your MT5 Expert Advisor to connect with the middleware.


2. Start the bot and let it handle trade communication.


3. Test on a Paper Account first before going Live.




---

📷 Demo

> (You can add GIFs / screenshots of the bot in action here for better presentation.)




---

🤝 Contribution

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.


---

📜 License

This project is licensed under the MIT License – free to use, modify, and distribute.


---

<p align="center">💡 Built with ❤️ by <b>Kamran Ali</b> | 24/7 Support Available</p>
