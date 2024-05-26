# Soroba Vote Dapp with Freighter Wallet
The Voting DAO app on Soroban leverages the cutting-edge features of Stellar's smart contract platform to facilitate decentralized decision-making within organizations. By utilizing Soroban's robust and scalable blockchain infrastructure, the app ensures secure, transparent, and efficient voting processes. Members of the DAO can propose, debate, and vote on various initiatives, with each action being recorded immutably on the blockchain. The app supports customizable voting mechanisms, such as single-choice, multiple-choice, and weighted voting, enabling DAOs to tailor the decision-making process to their specific needs. Additionally, Soroban's integration with Stellar's network ensures fast transaction times and low fees, making it an ideal solution for organizations of all sizes looking to implement a reliable and democratic governance structure. 

<img src="https://raw.githubusercontent.com/net2devcrypto/misc/main/vote5.png" width="550" height="370">
<img src="https://raw.githubusercontent.com/net2devcrypto/misc/main/vote6.png" width="550" height="370">

<h3>Repo Instructions</h3>

<h4>Step 1</h4>

Download or clone this repo, then open the folder in VScode and 

<h4>Step 2</h4>

Navigate to the repo folder once downloaded or cloned then install the NextJS instance.

```shell
cd name-of-folder
npm i
```

<h4>Step 3</h4>

Update the contract address in the soroban.js file with the one obtained on step 1. 

```shell
let contractAddress = 'CAAN5X32XWBIX3Q52BR4AJDVBAXPC5M3MVVPAVE5HVES2VWJBPO573L2';
```

CTRL + S to save file!

<h4>Step 4</h4>

Install the Freighter browser wallet then create your wallet account. Switch it to testnet and fund with friendlybot tokens. (All done in the wallet app)

<h5>Step 5</h5>

Run the app, access it and test!

```shell
cd name-of-folder
npm run dev
```

App should be accessible via: https://localhost:3000