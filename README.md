*This repo is a work in progress*

# Blockchain Developer, Smart Contract, & Solidity Course - Powered By AI - Beginner to Expert Course | Foundry Edition 2023

Welcome to the repository for the Blockchain Developer, Smart Contract, & Solidity Course - Powered By AI - Beginner to Expert Course | Foundry Edition 2023

*Video coming soon...*

Recommended Testnet: Sepolia

# [Testnet Faucets](https://faucets.chain.link)
Main Faucet:<a href="https://faucets.chain.link" target="_blank"> https://faucets.chain.link</a>
Backup Faucet:<a href="https://sepoliafaucet.com/" target="_blank"> https://sepoliafaucet.com/</a>

> ⚠️ All code associated with this course is for demo purposes only. They have not been audited and should not be considered production ready. Please use at your own risk. 

# Resources For This Course

### Questions

- [ChatGPT](https://chat.openai.com/)
    - Just know that it will often get things wrong, but it's very fast!
- [Phind](https://www.phind.com/)
    - Like ChatGPT, but it searches the web
- [Other AI extensions](https://twitter.com/aisolopreneur/status/1654823630155464704?s=42&t=-pu_sCYtfrfPJU7OXfifrQ)
- Github Discussions 
    -   Ask questions and chat about the course here!
-   [Stack Exchange Ethereum](https://ethereum.stackexchange.com/)
    -   Great place for asking technical questions about Ethereum
-   [Peeranha](https://peeranha.io/)
    -   Decentralized Stack Exchange!


New: Each lesson gets an NFT, and a "where to learn more" section. Maybe on ZKSync? Have a section be "moving funds to an L2". 

TODO: Add gitpod

- [Blockchain Developer, Smart Contract, \& Solidity Course - Powered By AI - Beginner to Expert Course | Foundry Edition 2023](#blockchain-developer-smart-contract--solidity-course---powered-by-ai---beginner-to-expert-course--foundry-edition-2023)
- [Testnet Faucets](#testnet-faucets)
- [Resources For This Course](#resources-for-this-course)
    - [Questions](#questions)
- [Lesson 0: Welcome to the Course!](#lesson-0-welcome-to-the-course)
- [Lesson 1: Blockchain Basics](#lesson-1-blockchain-basics)
- [Lesson 2: Welcome to Remix - Remix Simple Storage](#lesson-2-welcome-to-remix---remix-simple-storage)
  - [TODO: Extra credit / Exersizes!](#todo-extra-credit--exersizes)
- [Lesson 3: Remix Storage Factory](#lesson-3-remix-storage-factory)
  - [TODO: Extra credit / Exersizes!](#todo-extra-credit--exersizes-1)
- [Lesson 4: Remix Fund Me](#lesson-4-remix-fund-me)
  - [TODO: Extra credit / Exersizes!](#todo-extra-credit--exersizes-2)
- [Lesson 5: AI Prompting, Asking Questions, and Getting Help](#lesson-5-ai-prompting-asking-questions-and-getting-help)
- [Lesson 6: Foundry Simple Storage](#lesson-6-foundry-simple-storage)
  - [Installation \& Setup (MacOS \& Linux)](#installation--setup-macos--linux)
    - [Windows Setup](#windows-setup)
    - [Gitpod](#gitpod)
  - [Local Development Introduction](#local-development-introduction)
  - [Deploying to a testnet or a mainnet](#deploying-to-a-testnet-or-a-mainnet)
  - [TODO: Add FCC bash lessons](#todo-add-fcc-bash-lessons)
  - [TODO: Extra credit / Exersizes!](#todo-extra-credit--exersizes-3)
- [Lesson 7: Foundry Fund Me](#lesson-7-foundry-fund-me)
  - [Introduction](#introduction)
  - [Setup](#setup)
  - [Mocking](#mocking)
  - [Networking](#networking)
  - [Programmatic Verification](#programmatic-verification)
  - [Interactions.s.sol](#interactionsssol)
  - [Testing](#testing)
  - [Debugging \& Coverage](#debugging--coverage)
  - [Style Guide](#style-guide)
  - [Gas III](#gas-iii)
  - [Storage](#storage)
  - [Pushing to GitHub](#pushing-to-github)
- [TODO: Fix the tweet for paradigm instead of hardhat](#todo-fix-the-tweet-for-paradigm-instead-of-hardhat)
  - [🐸🐦 Tweet Me (add your repo in)!](#-tweet-me-add-your-repo-in)
  - [Recap](#recap)
- [Lesson 8: Html/Js Fund Me (Quick Fullstack / Front End Tutorial)](#lesson-8-htmljs-fund-me-quick-fullstack--front-end-tutorial)
- [Lesson 9: Foundry Smart Contract Lottery](#lesson-9-foundry-smart-contract-lottery)
  - [Raffle.sol Setup](#rafflesol-setup)
  - [Introduction to Events](#introduction-to-events)
  - [Events in Raffle.sol](#events-in-rafflesol)
  - [Introduction to Chainlink VRF](#introduction-to-chainlink-vrf)
    - [Sub-Lesson: Chainlink VRF](#sub-lesson-chainlink-vrf)
  - [Implementing Chainlink VRF - Introduction](#implementing-chainlink-vrf---introduction)
  - [Implementing Chainlink VRF - The Request](#implementing-chainlink-vrf---the-request)
  - [Implementing Chainlink VRF - The FulFill](#implementing-chainlink-vrf---the-fulfill)
    - [Modulo](#modulo)
  - [CEI](#cei)
  - [Introduction to Chainlink Automation](#introduction-to-chainlink-automation)
  - [Implementing Chainlink Keepers - checkUpkeep](#implementing-chainlink-keepers---checkupkeep)
    - [Enums](#enums)
  - [Implementing Chainlink Keepers - checkUpkeep continued](#implementing-chainlink-keepers---checkupkeep-continued)
  - [Implementing Chainlink Keepers - performUpkeep](#implementing-chainlink-keepers---performupkeep)
  - [Code Cleanup](#code-cleanup)
  - [Deploying Raffle.sol](#deploying-rafflesol)
    - [Mock Chainlink VRF Coordinator](#mock-chainlink-vrf-coordinator)
    - [Continued](#continued)
  - [Raffle.sol Unit Tests](#rafflesol-unit-tests)
    - [Testing Events](#testing-events)
    - [Continued I](#continued-i)
  - [Cheatcodes - vm.warp](#cheatcodes---vmwarp)
    - [Continued II](#continued-ii)
  - [Callstatic](#callstatic)
    - [Continued III](#continued-iii)
    - [Continued IV](#continued-iv)
  - [Raffle.sol Staging Tests](#rafflesol-staging-tests)
  - [Testing on a Testnet](#testing-on-a-testnet)
    - [Recommended LINK amounts for Sepolia Staging Test:](#recommended-link-amounts-for-sepolia-staging-test)
  - [Conclusion](#conclusion)
- [Lesson 10: Foundry ERC20s](#lesson-10-foundry-erc20s)
  - [What is an ERC? What is an EIP?](#what-is-an-erc-what-is-an-eip)
  - [What is an ERC20?](#what-is-an-erc20)
  - [Manually Creating an ERC20 Token](#manually-creating-an-erc20-token)
  - [Creating an ERC20 Token with Openzeppelin](#creating-an-erc20-token-with-openzeppelin)
  - [Lesson 12 Recap](#lesson-12-recap)
- [Lesson 11: Foundry NFTs | MoodNFT](#lesson-11-foundry-nfts--moodnft)
  - [What is an NFT?](#what-is-an-nft)
  - [Code Overview](#code-overview)
  - [Foundry Setup](#foundry-setup)
  - [Basic NFT](#basic-nft)
    - [Write Tests](#write-tests)
  - [IPFS NFT](#ipfs-nft)
    - [Setting an NFT Mint Price](#setting-an-nft-mint-price)
    - [Deploy Script](#deploy-script)
    - [Uploading Token Images with Pinata](#uploading-token-images-with-pinata)
    - [Uploading Token URIs (metadata) with Pinata](#uploading-token-uris-metadata-with-pinata)
    - [Deploying](#deploying)
    - [Tests](#tests)
  - [SVG On-Chain NFT](#svg-on-chain-nft)
    - [What is an SVG?](#what-is-an-svg)
    - [Initial Code](#initial-code)
    - [Base64 Encoding](#base64-encoding)
  - [Advanced: EVM Opcodes, Encoding, and Calling](#advanced-evm-opcodes-encoding-and-calling)
    - [abi.encode \& abi.encodePacked](#abiencode--abiencodepacked)
    - [Introduction to Encoding Function Calls Directly](#introduction-to-encoding-function-calls-directly)
    - [Introduction to Encoding Function Calls Recap](#introduction-to-encoding-function-calls-recap)
    - [Encoding Function Calls Directly](#encoding-function-calls-directly)
    - [Creating an NFT TokenURI on-Chain](#creating-an-nft-tokenuri-on-chain)
    - [Deploy Script](#deploy-script-1)
  - [Deploying the NFTs to a Testnet](#deploying-the-nfts-to-a-testnet)
  - [Lesson 14 Recap](#lesson-14-recap)
- [Lesson 12: Foundry DeFi | Stablecoin](#lesson-12-foundry-defi--stablecoin)
- [Lesson 13: Fuzzy Basket](#lesson-13-fuzzy-basket)
- [Lesson 14: Foundry DeFi | Stablecoin level up](#lesson-14-foundry-defi--stablecoin-level-up)
- [Lesson 15: Foundry Upgrades](#lesson-15-foundry-upgrades)
- [Lesson 16: Foundry Governance | Plutocracy (And why it's bad)](#lesson-16-foundry-governance--plutocracy-and-why-its-bad)
- [Lesson 17: Introduction to Smart Contract Security (Get to this section!!)](#lesson-17-introduction-to-smart-contract-security-get-to-this-section)


# Lesson 0: Welcome to the Course!
- **Follow the repository:** While going through the course be 100% certain to follow along with the github repository. If you run into in an issue check the chronological-updates in the repo.
- **Be Active in the community:** Ask questions and engage with other developers going through the course in the discussions tab, be sure to go and say hello or gm! This space is different from the other industries, you don't have to be secretive; communicate, network and learn with others :)
- **Learn at your own pace:** It doesn't matter if it takes you a day, a week, a month or even a year. Progress >>> Perfection
- **Take Breaks:** You will exhaust your mind and recall less if you go all out and watch the entire course in one sitting. 
  **Suggested Strategy** every 25 minutes take a 5 min break, and every 2 hours take a longer 30 min break
- **Refer to Documentation:** Things are constantly being updated, so whenever Patrick opens up some documentation, open it your end and maybe even have the code sample next to you.
- **Use ChatGPT and/or the course chat**

# Lesson 1: Blockchain Basics
<same as the 32 hour course, but add in L2s>
<Add PoS>
<add optimistic vs zk L2>
<talk about side chain>

Wallets:
- [Metamask](https://metamask.io/)
- [Frame](https://frame.sh/)

# Lesson 2: Welcome to Remix - Remix Simple Storage

💻 Code: [https://github.com/ChainAccelOrg/remix-simple-storage-f23](https://github.com/ChainAccelOrg/remix-simple-storage-f23)

## TODO: Extra credit / Exersizes!

1. Deploy a contract to <L2>

# Lesson 3: Remix Storage Factory

💻 Code: [https://github.com/ChainAccelOrg/remix-storage-factory-f23](https://github.com/ChainAccelOrg/remix-storage-factory-f23)

## TODO: Extra credit / Exersizes!

1. Deploy a contract to <L2>

# Lesson 4: Remix Fund Me

💻 Code: [https://github.com/ChainAccelOrg/remix-fund-me-f23](https://github.com/ChainAccelOrg/remix-fund-me-f23)

## TODO: Extra credit / Exersizes!
Deploy to L2

# Lesson 5: AI Prompting, Asking Questions, and Getting Help

DO NOT SKIP THIS!!

# Lesson 6: Foundry Simple Storage

💻 Code: [https://github.com/ChainAccelOrg/foundry-simple-storage-f23](https://github.com/ChainAccelOrg/foundry-simple-storage-f23)

## Installation & Setup (MacOS & Linux)
-   [Visual Studio Code](https://code.visualstudio.com/)
    - [Crash Course](https://www.youtube.com/watch?v=WPqXP_kLzpo)
- [VSCode Keybindings](https://code.visualstudio.com/docs/getstarted/keybindings)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [What is a terminal?](https://code.visualstudio.com/docs/editor/integrated-terminal)

### Windows Setup
- [WSL](https://docs.microsoft.com/en-us/windows/wsl/install)
  - When working in WSL, use Linux commands instead of Windows commands
- [TroubleShooting](https://docs.microsoft.com/en-us/windows/wsl/troubleshooting)
- `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`

> ⚠️ Please use Gitpod as an absolute last resort
### Gitpod
- [Gitpod](https://www.gitpod.io/)
  - **If using this, NEVER share a private key with real money on Gitpod**
  - Ideally you figure out the MacOS, Linux, or Windows install though

## Local Development Introduction
- `CMD + K` or `CTRL + K` clears the terminal
- `mkdir ethers-simple-storage-fcc`
- `code .` to open VSCode in a new VSCode window

Also do advanced stuff like:
cast
anvil
tests

- Format your solidity code with: 
```json
    "[solidity]": {
        "editor.defaultFormatter": "NomicFoundation.hardhat-solidity"
    },
    "[javascript]":{
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
```
[Ganache](https://trufflesuite.com/ganache/)
[ETH JSON RPC](https://ethereum.github.io/execution-apis/api-documentation/)

2 Ways to deploy:
1. `forge create`
2. `forge script`

```bash
cast --to-base 0x01 dec
```

## Deploying to a testnet or a mainnet
- [Alchemy](https://alchemy.com/?a=673c802981)
- [Someone fix this please](https://github.com/foundry-rs/foundry/issues/3818)
- [Example verified contract](https://sepolia.etherscan.io/address/0xe2e9f468eb7f063aa01670bb4bce4119fb6e4b65#code)
- [ThirdWeb Deploy](https://thirdweb.com/deploy)

## TODO: Add FCC bash lessons

## TODO: Extra credit / Exersizes!
Deploy to L2

# Lesson 7: Foundry Fund Me

💻 Code:[https://github.com/ChainAccelOrg/foundry-fund-me-f23](https://github.com/ChainAccelOrg/foundry-fund-me-f23)
## Introduction 

## Setup
- [Dependencies](https://book.getfoundry.sh/projects/dependencies)

## Mocking
- [Mocking](https://stackoverflow.com/questions/2665812/what-is-mocking)
- [Aave Github](https://github.com/aave/aave-v3-core)
- [Chainlink Github](https://github.com/smartcontractkit/chainlink)
- Multiple Versions of Solidity

## Networking
- [Chain ID List](https://chainlist.org/)

## Programmatic Verification
- [Etherscan API Key](https://docs.etherscan.io/getting-started/viewing-api-usage-statistics)

## Interactions.s.sol

## Testing
4 test tiers

1. [Unit](https://en.wikipedia.org/wiki/Unit_testing)
2. Integration
3. Forked
4. Staging

We cover 1 and 3. 

## Debugging & Coverage
- [Chisel](https://github.com/foundry-rs/foundry/tree/master/chisel)
- [Gas Reporter](https://book.getfoundry.sh/forge/gas-reports)
- Coverage
- [console.log](https://book.getfoundry.sh/reference/forge-std/console-log?highlight=console#console-logging)

## Style Guide
- [Style Guide](https://docs.soliditylang.org/en/latest/style-guide.html)
  - [Chainlink Style Guide](https://github.com/smartcontractkit/chainlink/blob/develop/contracts/STYLE.md)
- [NatSpec](https://docs.soliditylang.org/en/latest/natspec-format.html)

## Gas III

## Storage
- [Storage Layout](https://docs.soliditylang.org/en/latest/internals/layout_in_storage.html)
- [Purpose of the memory keyword](https://stackoverflow.com/questions/33839154/in-ethereum-solidity-what-is-the-purpose-of-the-memory-keyword)

```
cast storage
```
- [Opcodes](https://ethereum.org/en/developers/docs/evm/opcodes/)
- [Opcodes by Gas](https://github.com/crytic/evm-opcodes)
- [Opcodes by Gas](https://evm.codes/)
- Append `s_` to storage variables
- Append `i_` to immutable variables
- Caps lock and underscore constant variables
- [Chainlink Solidity Style Guide](https://github.com/smartcontractkit/full-blockchain-solidity-course-js/issues/13)

## Pushing to GitHub
- [Git Docs](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [GitHub docs](https://docs.github.com/en)
- [Github Quickstart](https://docs.github.com/en/get-started/quickstart)
- [What is Git?](https://www.git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
- [The quickstart that we follow in the video](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github#adding-a-local-repository-to-github-using-git)
- [Learn about git and GitHub](https://www.youtube.com/watch?v=RGOj5yH7evk)

# TODO: Fix the tweet for paradigm instead of hardhat

## 🐸🐦 [Tweet Me (add your repo in)!](https://twitter.com/intent/tweet?text=I%20just%20made%20my%20first%20Smart%20Contract%20repo%20using%20@solidity_lang,%20@HardhatHQ,%20@chainlink,%20@AlchemyPlatform,%20and%20more!%0a%0aThanks%20@PatrickAlphaC!!)

## Recap

# Lesson 8: Html/Js Fund Me (Quick Fullstack / Front End Tutorial)

💻 Code: [https://github.com/ChainAccelOrg/html-fund-me-f23](https://github.com/ChainAccelOrg/html-fund-me-f23)

# Lesson 9: Foundry Smart Contract Lottery

💻 Code: [https://github.com/ChainAccelOrg/foundry-smart-contract-lottery-f23](https://github.com/ChainAccelOrg/foundry-smart-contract-lottery-f23)

- debug TX

## Raffle.sol Setup
* Raffle.sol Setup
- Custom Errors in Solidity
## Introduction to Events
* Introduction to Events
- Events & Logging Video
- Events & Logging in Hardhat
## Events in Raffle.sol
* Events in Raffle.sol
## Introduction to Chainlink VRF
* Introduction to Chainlink VRF
- Special Guest <>
### Sub-Lesson: Chainlink VRF
> - Chainlink VRFv2 Docs
> - Chainlink VRFv2 Walkthrough
> - Chainlink Contracts
## Implementing Chainlink VRF - Introduction
* Implementing Chainlink VRF
## Implementing Chainlink VRF - The Request
## Implementing Chainlink VRF - The FulFill
### Modulo
- Modulo
## CEI
## Introduction to Chainlink Automation
- Chainlink Automation Docs
- Chainlink Automation Walkthrough
## Implementing Chainlink Keepers - checkUpkeep
### Enums
- Enum
## Implementing Chainlink Keepers - checkUpkeep continued
- block.timestamp
## Implementing Chainlink Keepers - performUpkeep
## Code Cleanup
## Deploying Raffle.sol
### Mock Chainlink VRF Coordinator
### Continued
- LINK Token
## Raffle.sol Unit Tests
### Testing Events
### Continued I
## Cheatcodes - vm.warp
### Continued II
## Callstatic
- Callstatic
### Continued III
### Continued IV
## Raffle.sol Staging Tests
## Testing on a Testnet
### Recommended LINK amounts for Sepolia Staging Test:
- Chainlink VRF: 2 LINK
- Chainlink Keepers: 8 LINK
## Conclusion

# Lesson 10: Foundry ERC20s

💻 Code: [https://github.com/ChainAccelOrg/foundry-erc20-f23](https://github.com/ChainAccelOrg/foundry-erc20-f23)

## What is an ERC? What is an EIP?
- What is an EIP?
- EIPs codebase
## What is an ERC20?
- Video (using brownie/python)
- EIP-20
- ERC-677
- EIP-777
## Manually Creating an ERC20 Token
- `.github`
## Creating an ERC20 Token with Openzeppelin
- Openzeppelin
- Openzeppelin Contracts
- Solmate (Openzeppelin alternative)
## Lesson 12 Recap


# Lesson 11: Foundry NFTs | MoodNFT

💻 Code: [https://github.com/ChainAccelOrg/foundry-nft-f23](https://github.com/ChainAccelOrg/foundry-nft-f23)


## What is an NFT? 
- Video
- Optional: All on Chain SVG NFT
- EIP-721
## Code Overview
## Foundry Setup
## Basic NFT
### Write Tests 
- Openzeppelin NFT
## IPFS NFT
### Setting an NFT Mint Price
### Deploy Script
### Uploading Token Images with Pinata
- Pinata
- nft.storage
- Pinata NPM
- Pinata Docs
### Uploading Token URIs (metadata) with Pinata
### Deploying
### Tests
## SVG On-Chain NFT
- Patrick's Original Video
### What is an SVG?
- SVG Tutorial
  - On-Chain SVG Example
### Initial Code  
### Base64 Encoding
- Base64 Encoding
  - Example Encoder
- base64-sol
## Advanced: EVM Opcodes, Encoding, and Calling
### abi.encode & abi.encodePacked
- abi.encode
- abi.encodePacked
Thanks to [Alex Roan](https://twitter.com/alexroan) for his help on this session!
- Example Contract Creation Transaction
What REALLY is the ABI?
- EVM Opcodes
- More EVM Opcodes
- Solidity Cheatsheet
- abi.encode vs abi.encodePacked
### Introduction to Encoding Function Calls Directly
### Introduction to Encoding Function Calls Recap
### Encoding Function Calls Directly
- Function Selector
- Function Signature
### Creating an NFT TokenURI on-Chain
### Deploy Script
## Deploying the NFTs to a Testnet
## Lesson 14 Recap


- [ENS](https://ens.domains/)

# Lesson 12: Foundry DeFi | Stablecoin

MEV

# Lesson 13: Fuzzy Basket

Fuzz Testing

# Lesson 14: Foundry DeFi | Stablecoin level up

# Lesson 15: Foundry Upgrades

# Lesson 16: Foundry Governance | Plutocracy (And why it's bad)

# Lesson 17: Introduction to Smart Contract Security (Get to this section!!)
- Reentrancy
- Symbolic Execution
- Flash loans
