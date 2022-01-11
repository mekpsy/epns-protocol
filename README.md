# EPNS Protocol Overview

EPNS high level Protocol architecture
EPNS has been on its mission to build the most effective and reliable communication layer on Web3 to allow sending notifications in a platform-agnostic and decentralized fashion.
While the initial idea was to build a notification protocol on Ethereum blockchain specifically, we have always had the vision to become Blockchain agnostic. With this goal in mind, the EPNS smart contracts have been modified accordingly to support these features.
The EPNS Protocol has now been divided into two different smart contracts, i.e., EPNS Core & EPNS Communicator.

![](https://i.imgur.com/TGxNEMO.png)


## 1. EPNS Core Protocol:
The EPNSCore protocol, as the name might indicate, is the main smart contract as ***it handles some of the most crucial features like Channel creation, governance, channel state changes as well as funds and incentive mechanisms, etc.
It’s very important to note, however, that the EPNS Core smart contract will only be deployed on the Ethereum blockchain and not on any other chain.***


## 2. EPNS Communicator Protocol:
Unlike the EPNS Core smart contract, the communicator protocol is designed to be deployed on multiple chains.

The EPNS Communicator protocol is comparatively quite simple. The communicator protocol includes features that ***allow users to subscribe to a channel, unsubscribe from a channel as well as the imperative one, i.e., sending notifications***.

As the ***communicator protocol can be deployed on multiple chains, it allows us to trigger notifications on multiple chains and not just the Ethereum blockchain***.
