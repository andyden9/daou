### Introduction

DAOU uses Soulbound Token and Social Oracle to convert your activity data in DAOs: Discord activity and engagement, Forum Q&A, Github code contributions, DAO roles and connections into on-chain verifiable data. Social Oracle refers to incentivizing members in the same DAO to sign and verify the data generated by DAO members, thus making these data more credible, and giving each member a score based on these data, this score will be the member Credit in DAO. The data verified by Social Oracle will be released to Soulbound Token by DAO, which can then be used externally. For example:

- Credit loan
- Airdrops for Soulbound Token Holders
- Prevent DDoS
- ...

![daou.png](https://s2.loli.net/2022/05/31/6wTpevNtSBqY8u4.png)

### Social Capital

Briefly: When you want to do something, how many people are willing to support you based on their understanding of you and social identity.

### Soulboun Token

A new kind of NFT – nontransferable & nontradable – to be held in your wallet, called a soul, forever.


### tech

- Client: Using React, Next, Rainbowkit
- [Server](https://github.com/DAOU-IO/daou/tree/main/server): Using Firebase
- [Smart Contracts](https://github.com/DAOU-IO/daou/tree/main/contracts)：Test with Hardhat
  - [SoulBound Token](https://github.com/DAOU-IO/daou/blob/main/contracts/contracts/SBT.sol)
  - [Social Oracle](https://github.com/DAOU-IO/daou/blob/main/contracts/contracts/SocialOracle.sol)
  - [Test](https://github.com/DAOU-IO/daou/tree/main/contracts/test)

All work done by [Tingfei](https://twitter.com/fifteen42_).