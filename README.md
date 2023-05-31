# Avax Gods NFT Card Game
An NFT card game utilising the power of Avalanche and React.js

## Check out a live version [here](https://lucky-toffee-c06b6c.netlify.app/)

![Game Preview](/nft_card_game_promoimg.PNG)

Created an NFT card game utilizing Solidity and the Avalanche network and Core wallet for the backend, and React.js and Tailwind for the frontend to create a clean and fun multiplayer NFT card game. Players register their name and wallet, create or join a battle and then play online against other competitors. Health points, mana and the attack and defense values are all linked and function so strategy must be used to win and get the opposing players health to zero before they defeat you. The tutorial was created by JSMastery.

---

## Technologies

This repository utilises Hardhat and React.js:
* [Hardhat](https://hardhat.org/) - Solidity technology
* [Core Wallet](https://core.app/en/) - an Avalanche wallet to allow for interaction with the blockchain
* [React.js](https://react.dev/) - Frontend JavaScript language



---

## Installation Guide

1. `cd web3`
2. `npx hardhat` -> y → typescript → enter → enter
3. `npm install @openzeppelin/contracts dotenv @nomiclabs/hardhat-ethers` + Hardhat packages `npm install --save-dev "hardhat@^2.12.0" "@nomicfoundation/hardhat-toolbox@^2.0.0"`
4. Install [Core](https://chrome.google.com/webstore/detail/core/agoakfejjabomempkjlepdflaleeobhb), a Metamask smart wallet alternative built for Avalanche dApps
  i. Turn on the testnet mode by: opening up the Core extension -> click the hamburger menu on the top left -> go to advanced -> turn on the testnet mode
5. Fund your wallet from the [Avax Faucet](https://faucet.avax.network/)
6. Update the `.env` file and add your PRIVATE_KEY variable.
7. To get to the private key, do the following steps:
  i. Open up the Core extension -> click the hamburger menu on the top left -> go to security and privacy -> click show recovery phase -> enter your password -> copy the phrase -> go to [wallet.avax.network](https://wallet.avax.network/) -> click access wallet -> choose mnemonic key phrase -> paste what the words we’ve copied from Core -> on the sidebar click manage keys -> view c-chain private key -> copy -> paste it in the .env file
8. Compile the contract by running the `npx hardhat compile` command
9. Deploy the smart contract on the Fuji test network by running the `npx hardhat run scripts/deploy.ts --network fuji` command
  Move the `/artifacts/contracts/AVAXGods.json` file to the `/contract` folder on the frontend
  Copy the address of the deployed contract from the terminal and paste it into the `/contract/index.js` file of the frontend application

---  

### **Run instructions:**
To test this game and play for yourself, the link is at the top of the ReadMe file or you can click [here](https://lucky-toffee-c06b6c.netlify.app/).

If you want to recreate it yourself using the files:

- Add the contract address to 'ADDRESS' in '/client/src/contract/index.js'
- Add your Core wallet private key to '/web3/.env' | DO NOT SHARE YOUR PRIVATE KEY WITH ANYONE ELSE OR MAKE IT PUBLIC
- Make sure to have Fuji testnet Avax in your wallet. You can request 2 Avax per day from the [Avalanche Faucet](https://faucet.avax.network/)

---
## Avax Gods

1. Connect your wallet to the site.
2. Register your name and wallet.
3. Create a battle or join.
4. The rules of the game are located in the menu within the battle section or as follows:
  'Card with the same defense and attack point will cancel each other out.',
  'Attack points from the attacking card will deduct the opposing player’s health points.',
  'If P1 does not defend, their health wil be deducted by P2’s attack.',
  'If P1 defends, P2’s attack is equal to P2’s attack - P1’s defense.',
  'If a player defends, they refill 3 Mana',
  'If a player attacks, they spend 3 Mana'.
5. Can forfeit the game through sidebar or the game will automatically return to the 'create-battle' page.
6. Note: there have been some known issues, if nothing happens, refresh and it should fix the issue.


---

## Disclaimer

This project used test net accounts and cryptocurrency for practise purposes.

---

## Contributors

**This project was created by [JS Mastery](jsmastery.pro) for teaching purposes and then recreated by Lachlan Andrews**

Lachlan Andrews

Email: swerdna14@gmail.com

LinkedIn: [lachlanjandrews](https://www.linkedin.com/in/lachlanjandrews/)
