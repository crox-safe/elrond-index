# elrond-index
This repository will have an index for developers to have an easier access to the elrond network.


### Network Layer - Core
[elrond-go:](https://github.com/ElrondNetwork/elrond-go) GO implentation to join to the Elrond Network as a observer or as a validator
### Setups
[elrond-go-scripts:](https://github.com/ElrondNetwork/elrond-go-scripts) Repository for installing, managing and benchmarking Elrond nodes. Works with [mainnet](https://github.com/ElrondNetwork/elrond-go-scripts-mainnet), [devnet](https://github.com/ElrondNetwork/elrond-go-scripts-devnet), [testnet](https://github.com/ElrondNetwork/elrond-go-scripts-testnet).
- Mainnet: 

### APIs
[elrond-proxy-go:](https://github.com/ElrondNetwork/elrond-proxy-go) Is the gateway to use it on sdks like erdpy, erdjs, etc. Is the intermediary between the client layer and the elrond network layer.

[api.elrond.com:](https://github.com/ElrondNetwork/api.elrond.com) Is a layer on top of elrond-proxy-go that adds access to historical data, caching and other endpoints

### Smart Contracts Layer
[arwen-wasm-vm:](https://github.com/ElrondNetwork/arwen-wasm-vm)The virtual machine to run smart contracts in Elrond Network

[elrond-wasm-rs:](https://github.com/ElrondNetwork/elrond-wasm-rs)Rust smart contract library designed for Elrond's Arwen VM

### SDKs
🛠 Elrond - Command Line Tools and SDK (Python, TypeScript, Go, Java) for interacting with the Elrond Network (in general) and Smart Contracts (in particular).
- Python | [erdpy](https://github.com/ElrondNetwork/elrond-sdk-erdpy)
- GO | [erdgo](https://github.com/ElrondNetwork/elrond-sdk-erdgo)
- Java | [erdjava](https://github.com/ElrondNetwork/elrond-sdk-erdjava)
- C++ | [erdcpp](https://github.com/ElrondNetwork/elrond-sdk-erdcpp)
- JS, TS | [erdjs](https://github.com/ElrondNetwork/elrond-sdk-erdjs)
- Kotlin | [erdkotlin](https://github.com/ElrondNetwork/elrond-sdk-erdkotlin)

## Examples & End User Integration

### DApps examples
 - [dapp:](https://github.com/ElrondNetwork/dapp) NPM pacakge for authentication and transaction execution on the elrond blockchain
Skills: React.js, TS
 - [dapp-template:](https://github.com/ElrondNetwork/dapp-template) React and TS app providing the basics for Elrond authentication and TX signing
Skills: React.js, TS
- [dapp-utils:](https://github.com/ElrondNetwork/dapp-utils)  A collection of react components and helper functions commonly used when developing DApps
Skills: React.js, TS
 - [starter-dapp:](https://github.com/ElrondNetwork/starter-dapp) Elrond DApps examples
Skills: React.js, TS

### Smart Contracts Examples
 - [ping-pong-smart-contract:](https://github.com/ElrondNetwork/ping-pong-smart-contract) A simple contract that allows sending a certain amount of sum like a ping pong method
 - [sc-dex-rs:](https://github.com/ElrondNetwork/sc-dex-rs) Smart contracts for a decentralized exchange | Maiar Contracts
 - [sc-launchpad-rs:](https://github.com/ElrondNetwork/sc-launchpad-rs) Smart contracts for a launchpad on Elrond Network
 - [sc-nft-marketplace:](https://github.com/ElrondNetwork/sc-nft-marketplace) Smart contract to deploy an NFT market
 - [sc-stablecoin-rs:](https://github.com/ElrondNetwork/sc-stablecoin-rs) Smart contracts for an over-collateralized stablecoin
 - [sc-distribution-rs:](https://github.com/ElrondNetwork/sc-distribution-rs) Smart Contract used to distribute ESDT tokens 
 - [sc-chainlink-rs:](https://github.com/ElrondNetwork/sc-chainlink-rs) Chainlink Oracle smart contracts on Elrond ecosystem
 - [sc-bridge-elrond:](https://github.com/ElrondNetwork/sc-bridge-elrond) Smart contracts on the Elrond side to do a bridge swap corss-chain | Elrond TX <—> Ethereum TX
 - [sc-savings-account-rs:](https://github.com/ElrondNetwork/sc-savings-account-rs) Saving Account Smart Contract which use borrow payment method
 - [sc-flash-mint-rs:](https://github.com/ElrondNetwork/sc-flash-mint-rs) Smart Contract flash loan provider that does not require providers to add funds


## Diagram
![elrondgithub](https://user-images.githubusercontent.com/82739614/134298491-1aed0084-b544-4aec-99a5-f21ec0d9bd68.png)
