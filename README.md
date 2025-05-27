# Kite-AI-Ozone-BOT
Auto Complete Daily Quiz Auto Stake &amp; Unstake KITE Token Auto Interaction With Kite AI Agents Multi Accounts

![image](https://github.com/user-attachments/assets/914d68a9-e51a-4849-aee6-87a81ddd43fb)
![image](https://github.com/user-attachments/assets/20252b62-23fa-4dfd-918d-811a549dd236)



Kite AI Ozone Automation Bot
Welcome to the Kite AI Ozone Bot, a powerful tool designed to automate interactions with the Kite AI Ozone Testnet. This bot simplifies tasks like account management, staking, quizzes, and AI agent interactions, supporting single or multiple accounts with flexible proxy options. Follow this guide to set up, configure, and run the bot efficiently.
Features

Automated Account Info Retrieval: Fetch account details seamlessly.
Proxy Support:
Option 1: Run with Monosans proxy.
Option 2: Run with private proxy.
Option 3: Run without proxy.


Proxy Rotation: Automatically rotate invalid proxies (configurable: yes/no).
Daily Quiz Automation: Complete daily quizzes to earn XP.
KITE Token Management: Auto-stake and unstake KITE tokens.
AI Agent Interaction: Engage with Kite AI agents automatically.
Multi-Account Support: Manage multiple EVM wallets effortlessly.

Prerequisites
Ensure you have the following installed:

Python: Version 3.9 or higher.
pip: Python package manager.
An EVM-compatible wallet (e.g., MetaMask).
Optional: Proxy service for enhanced privacy.

Installation

Clone the Repository:
git clone https://github.com/rajatj86/KiteAI-AutoBot.git
cd KiteAI-AutoBot


Install Dependencies:
pip install -r requirements.txt


Note: If errors occur, verify the versions of cryptography and eth-account libraries match those in requirements.txt.





Configuration
Configure the bot by setting up the following files in the project directory:
accounts.txt

Contains your EVM wallet addresses.
Format (one address per line):0xYourEvmAddress1
0xYourEvmAddress2



proxy.txt

Contains proxy details for network requests.
Supported formats:ip:port  # Default: HTTP
protocol://ip:port
protocol://user:pass@ip:port



Running the Bot

Ensure accounts.txt and proxy.txt are configured correctly.
Run the bot:python bot.py


Note: Use python3 bot.py if python refers to Python 2 on your system.



Proof of Bot Running
To demonstrate the bot is operational, you can record its execution and share the results. Below is an example of how to verify and showcase the bot’s functionality:
Example Output
After running python bot.py, the bot logs its actions to the console. A sample log might look like this:
[2025-05-27 12:15:34] INFO: Bot started for account 0xYourEvmAddress1
[2025-05-27 12:15:35] SUCCESS: Connected to Kite AI Ozone Testnet
[2025-05-27 12:15:36] INFO: Claiming daily quiz for account 0xYourEvmAddress1
[2025-05-27 12:15:38] SUCCESS: Quiz completed, earned 50 XP
[2025-05-27 12:15:40] INFO: Staking 100 KITE tokens
[2025-05-27 12:15:42] SUCCESS: Tokens staked successfully
[2025-05-27 12:15:45] INFO: Interacting with AI agent
[2025-05-27 12:15:47] SUCCESS: AI agent interaction completed

Screenshot/Video Proof

Console Output: Take a screenshot of the terminal showing the bot’s logs (like the example above).
Testnet Dashboard: Capture a screenshot of the Kite AI Testnet dashboard (https://testnet.gokite.ai) showing updated XP, staked tokens, or badges for your account.
Video Demo (optional): Record a short video of the bot running, showing the terminal and dashboard updates. Host the video on a platform like YouTube or a cloud service and link it in your repository.

Sharing Proof

Add to Repository: Create a proof/ directory in your repository and include screenshots or a link to the video.mkdir proof
mv screenshot.png proof/


Update README: Reference the proof in your README, e.g.:
See the proof/ directory for screenshots of the bot in action or watch the demo video.



Troubleshooting

Dependency Errors: Ensure all libraries match the versions in requirements.txt.
Proxy Issues: Verify proxy formats and test connectivity outside the bot.
Account Errors: Confirm EVM addresses are valid and have access to the Kite AI Testnet.
Need Help?: Check the Kite AI FAQs or join the Kite AI Discord for support.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature/YourFeature).
Commit changes (git commit -m 'Add YourFeature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Built with ❤️ by Rajatj86


**Buy Me a Coffee**
EVM: 0x1157fC382df809c31A1E463cD874ea2D6d1773D2
SOL: 6xm42DigLjZ7N52CtP1ZXh7YWqZJMVStaagFcW1WckyV
SUI: 0x04f9bb97722293a27d9fd9b227f0aee0ddef78a4947d6105f5930a783d7fc021
Thank you for visiting this repository, don't forget to contribute in the form of follows and stars. If you have questions, find an issue, or have suggestions for improvement, feel free to contact me or open an issue in this GitHub repository.
