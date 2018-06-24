SimpleBlockchainApp
===================
A simple, fully-functional blockchain-based project which implements a public blockchain from scratch and a simple Flask web application to leverage it.

Project
-------
Objective: to build a simple web application using a public blockchain that allows users to share information over a decentralized network.
Because the content will be stored on the blockchain, it is immutable and permanent (more below).
Defining the structure of the data that will be stored on the blockchain:
A post is a message posted by any user on our application, it must have three properties: content, author, and timestamp.

Process
-------
Using Flask microframework, create endpoints for different functions of the blockchain, such as adding a transaction.
Then, run the scripts on multiple machines in order to create a decentralized network.
Build a simple UI that interacts with the blockchain and stores information for any use case.
For instance, content sharing, P2P payments, chatting, or e-commerce.

Background
----------
Public blockchain vs. Private blockchain
A public blockchain network is completely decentralized and open to the public.
No one entity has control over the network and they are secure in that data cannot be changed once validated on the blockchain.
Anyone can join and participate.
Examples: Bitcoin, Ethereum

A private blockchain network is primarily used by businesses who need greater privacy, security, and speed of transactions.
Participants need an invitation to join.
They operate quite similarly to public blockchains but have access controls that limit who can participate in the network.
It operates like modern centralized database systems that restrict access to certain users.
One or more entities control the network.
Causes users to still have to rely on third-parties to transact.
Example: Ripple, Hyperledger

In 2008, a whitepaper was released by an individual or group under the identifier Satoshi Nakamoto
Titled "Bitcoin: A Peer-to-Peer Electronic Cash System."
The paper combined cryptographic techniques and a peer-to-peer network without the need to trust a centralized authority to make payments from one person to another.
It also introduced a distributed system of storing data (blockchain).
We now know this concept has far wider applicability than just payments, or cryptocurrencies.
Blockchain technology has exploded across nearly every industry.
It is now the underlying technology behind:
- Fully digital cryptocurrencies (i.e., Bitcoin)
- Distributed copmuting technologies (i.e., Ethereum)
- Open-source frameworks (i.e., Hyperledger Fabric)

Blockchain Basics
-----------------
In simplest terms, blockchain is a mechanism for storing digital data.
The data can literally be anything.
The data can even be files, it doesn't matter.
In the case of Bitcoin, it is the transactions (transfers of Bitcoin from one account to another).
The data is stored in the form of blocks, which are chained together using hashes.
Storing data in BLOCKs + using hashes to CHAIN them together = blockchain

All of the "magic" in blockchain comes from the way this data is added and stored in the blockchain.
This yields some highly desirable and powerful characteristics:
- Immutability of history
- Un-hackability of the system
- Persistence of the data
- No single point of failure
