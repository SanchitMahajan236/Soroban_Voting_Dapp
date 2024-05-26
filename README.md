# Soroba Vote Dapp with Freighter Wallet
The Voting DAO app on Soroban leverages the cutting-edge features of Stellar's smart contract platform to facilitate decentralized decision-making within organizations. By utilizing Soroban's robust and scalable blockchain infrastructure, the app ensures secure, transparent, and efficient voting processes. Members of the DAO can propose, debate, and vote on various initiatives, with each action being recorded immutably on the blockchain. The app supports customizable voting mechanisms, such as single-choice, multiple-choice, and weighted voting, enabling DAOs to tailor the decision-making process to their specific needs. Additionally, Soroban's integration with Stellar's network ensures fast transaction times and low fees, making it an ideal solution for organizations of all sizes looking to implement a reliable and democratic governance structure. 

![Screenshot 2024-05-26 234012](https://github.com/SanchitMahajan236/Soroban_Voting_Dapp/assets/116559051/66bcfc55-caab-4ce5-aec8-fcbbe83b84e0)
![Screenshot 2024-05-26 234104](https://github.com/SanchitMahajan236/Soroban_Voting_Dapp/assets/116559051/13e08b05-1556-4ed6-812b-e3ccc59b35d0)
![Screenshot 2024-05-26 234307](https://github.com/SanchitMahajan236/Soroban_Voting_Dapp/assets/116559051/9e8c11a0-28d3-462e-914b-31388265b128)

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
