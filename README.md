# Avax Gods NFT Card Game
An NFT card game utilising the power of Avalanche and React.js

## Check out a live version [here](https://lucky-toffee-c06b6c.netlify.app/)

![Game Preview](/nft_card_game_promoimg.PNG)

This challenge required the creation of a streamlit application that makes hiring a FinTech freelancer easier! The application allows the user to select a freelancer and how many hours they wish to hire them for, and then it can send ETH directly into their wallet as payment. The screenshots below are from **Ganache**, an application that shows the transaction history, details and addresses that were used in the KryptoJobs2Go application, straight from the blockchain as evidence that the application has worked.

---

## Technologies

This repository utilises Hardhat and React.js:
* [Hardhat](https://streamlit.io/) - Solidity technology
* [Core Wallet](https://docs.python.org/3/library/os.html) - an Avalanche wallet to allow for interaction with the blockchain
* [React.js](https://docs.python-requests.org/en/master/) - Frontend JavaScript language



---

## Installation Guide

Install the Streamlit library using the following command: 'import streamlit as st'

Install the os library using the following command: 'import os'

Install the Requests library using the following command: 'import requests'

Install the dotenv library using the following command: 'from dotenv import load_dotenv'

Install the Dataclass library using the following command: 'from dataclasses import dataclass'

Install the BIP44 library using the following command: 'from bip44 import Wallet'

Install the web3 libraries using the following commands: 'from web3 import Account', 'from web3.auto.infura.kovan import w3', 'from web3 import middleware', 'from web3.gas_strategies.time_based import medium_gas_price_strategy'

---  

### **Run instructions:**
To test this game and play for yourself, the link is at the top of the ReadMe file or you can click [here](https://lucky-toffee-c06b6c.netlify.app/).

If you want to recreate it yourself using the files:

- Add the contract address to 'ADDRESS' in '/client/src/contract/index.js'
- Add your Core wallet private key to '/web3/.env' | DO NOT SHARE YOUR PRIVATE KEY WITH ANYONE ELSE OR MAKE IT PUBLIC

[https://faucet.avax.network/]

---
## Avax Gods

Using streamlit to run the KryptoJobs2Go application, it was created to inspect and hire a range of FinTech freelancers. The application displays an image of the freelancer, the cost per hour in ETH to hire them, their name, their Ethereum address, and their KryptoJobs2Go rating out of 5.


---

## Disclaimer

This project used test net accounts and cryptocurrency for practise purposes.

---

## Contributors

**This project was created by [JS Mastery](jsmastery.pro) for teaching purposes and then recreated by Lachlan Andrews**

Lachlan Andrews

Email: swerdna14@gmail.com

LinkedIn: [lachlanjandrews](https://www.linkedin.com/in/lachlanjandrews/)
