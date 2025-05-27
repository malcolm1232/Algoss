## 📚 Table of Contents

- [Project 1: cTrading Algorithms](https://github.com/malcolm1232/Algoss/tree/main/1_cTrader)
- 🔗 [My Live cTrader Portfolio (Click Me)](https://ct.spotware.com/investor/QlECLU8) (About 140% in 30 days)
  
<img src="ReadMe_files/74af8607-08ed-4418-a434-0c069ff71fa8.png" width="300"/>

- [Project 2: Reinforcement Learning on Order Book](https://github.com/malcolm1232/Algoss/tree/main/2_IBKR_TWS%20(Reinforcement%20Learning))
- [Project 3: AutomatedTradesFromScreenshot](https://github.com/malcolm1232/Algoss/tree/main/AutomatedTradesFromScreenshot)



# 📘 Project Portfolio: Quantitative Trading Systems

## Objective:
- Build, test, and automate trading strategies using:
  - Reinforcement Learning
  - Screenshot-to-trade automation
  - Order book analysis


### Some Open Source Algorithms on TradingView written in Pine Script and cTrader

## 📸 Screenshot Example of TradingView Algorithm 

![image.png](ReadMe_files/b6a65245-15d7-4984-b2bf-afa311cd2fd6.png)
- As you can see we have decent **profit factor**

![image.png](ReadMe_files/d862d432-b798-44cc-b5d1-6b8a45a2bd7b.png)
![image.png](ReadMe_files/c4f9404a-60ea-4274-b197-de7715ab52fb.png)

## 🧠 Project 2: Reinforcement Learning on IBKR Order Book

**Description:**  
Apply DQN to learn optimal trade actions based on order book (bid/ask) state snapshots from IBKR.

**Tech Stack:** Python, IB Gateway API, PyTorch, DQN, Numpy

**Key Outputs:**
- State representation of L2 order book
- Reward shaping with slippage penalty
- Epsilon decay, Q-visualization

📁 Files: `2_IBKR_TWS (Reinforcement Learning)/`

#### Result:
![image.png](ReadMe_files/5621394e-2d5b-4ae3-b44e-d6bc8d3e4b4c.png)

## 🔁 Project 3: Automated Trades from Screenshot

**Description:**  
Use OCR and GPT to extract trade signals from a screenshot and send live orders to cTrader.

**Tech Stack:** Python, Pytesseract, OpenAI GPT, WebSockets, cTrader API

**Key Features:**
- Extracts SL/TP/Entry from image
- Converts to JSON and sends to execution bot
- Mirrored execution + logging to Telegram

📁 Files: `AutomatedTradesFromScreenshot/`, `Automated_Trades.ipynb`

## Example Image Input:
![image.png](ReadMe_files/c95e401e-6e0f-4695-ac27-b6ccf11b7ca3.png)

or 

![image.png](ReadMe_files/4b4a9fa2-cd80-459c-8310-ad31bfbdae83.png)

## Example Output:
#### Place a Transaction and order confirmation sent to Telegram:
![image.png](ReadMe_files/a9988a7a-e5ff-4cba-8c4a-042446507100.png)

#### Copy (Professional) Full time Traders eg. from JPM, to leverage on their intellect to make it scalable.


```python
!jupyter nbconvert ReadMe.ipynb --to markdown
```
