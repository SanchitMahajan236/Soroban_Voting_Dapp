# Soroban Vote Dapp

![Screenshot 2024-05-28 155527](https://github.com/SanchitMahajan236/Soroban_Voting_Dapp/assets/116559051/3f14105e-624d-4592-828e-705341239c9b)

## About Me

Sanchit Mahajan, currently a student pursuing a Bachelors in Technology from Maharaja Agrasen Institute of Technology, a tech enthusiast mainly working with web2 technologies and expanding my knowlegde in web3. I have experience in Full-Stack Web Development and Flutter App Development, previously developed with smart contracts using soldity and in the bootcamp got to work with Rust for writing smart contracts. I am also a keen learner and an anime-lover.

## Description

The Voting DAO app on Soroban leverages the cutting-edge features of Stellar's smart contract platform to facilitate decentralized decision-making within organizations. By utilizing Soroban's robust and scalable blockchain infrastructure, the app ensures secure, transparent, and efficient voting processes. Members of the DAO can propose, debate, and vote on various initiatives, with each action being recorded immutably on the blockchain. The app supports customizable voting mechanisms, such as single-choice, multiple-choice, and weighted voting, enabling DAOs to tailor the decision-making process to their specific needs. Additionally, Soroban's integration with Stellar's network ensures fast transaction times and low fees, making it an ideal solution for organizations of all sizes looking to implement a reliable and democratic governance structure. 

## Vision

The vision for the Voting DAO app on Soroban is to revolutionize organizational governance by harnessing the power of blockchain technology to create a truly democratic, transparent, and efficient decision-making platform. We aim to empower decentralized autonomous organizations (DAOs) with a seamless and secure voting system that upholds the principles of fairness and inclusivity. By providing a flexible and customizable voting framework, we envision a future where organizations of all types and sizes can engage their members in meaningful participation, fostering collaboration and innovation. Our ultimate goal is to set a new standard for governance in the digital age, ensuring that every voice is heard and every vote counts in shaping the direction and success of DAOs worldwide.

## Programming Language

- Rust
- JavaScript
- Web3

## Setup Environment

<h4>Step 1</h4>

Download or clone this repo, then open the folder in VScode and in the terminal write:
```shell
cd soroban-vote-contract
cargo test
```
```shell
soroban contract build
```
```shell
cargo build --target wasm32-unknown-unknown --release
```
```shell
cargo install --locked soroban-cli --features opt
```
```shell
soroban contract optimize --wasm target/wasm32-unknown-unknown/release/hello_world.wasm
```
```shell
soroban network add `
  --global testnet `
  --rpc-url https://soroban-testnet.stellar.org:443 `
  --network-passphrase "Test SDF Network ; September 2015"
```
```shell
soroban keys generate --global alice --network testnet
```
```shell
soroban keys address alice
```
```shell
soroban contract deploy `
  --wasm target/wasm32-unknown-unknown/release/hello_world.wasm `
  --source alice `
  --network testnet
```
Save the generated code for later use.

<h4>Step 2</h4>

Navigate to the repo folder once downloaded or cloned then install the NextJS instance.

```shell
cd ..
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
npm run dev
```

App should be accessible via: https://localhost:3000
