# i8-exchange
this is HEX(Hybrid Exchange) with EOS blockchain


**[homepage](http://www.i8exchange.com/)**




## 1.Security of DEX (Distributed Exchange) (including reliability and transparency)

- USER ASSET MANAGEMENT: There is no need to deposit assets

- TRUSTRESS: There is no need to trust an exchange (run away, risk of hacking is low)
⇒ "Trustless" which is the characteristic of the block chain (trust is unnecessary for a third party) can be realized
⇒ There is little fear of hacking in storage or transactions
⇒ It is unlikely that personal assets will be lost due to the malice of others (there is little chance that regulation will take place as fraud is unlikely to occur)

- P2P: Since it is a relative transaction between customers, security is strong enough

- NoManager: Since there is no administrator, there is no need to send passwords or personal information to exchanges

- Fully Decentralized: Identity verification procedure, login etc. unnecessary (safety + easy to register)

- smart contract: encrypted and distributed among nodes. Specifically, this guarantees that it will not be lost or changed without your permission

- Each node with server: effect of down for infraction is limited (Reliability)


### 2-1. Development technology of DEX (Distributed Exchange)

Next Generation Virtual Currency / Encryption Currency Exchange System = Distributed Application (Dapp)

* Used to buy and sell ERC 20 tokens based on Ethereum (Ethereum)

* There are something which incorporate some centralized system to speed up the process

* There are something without Order Book

* System configuration
- Maintain asset management rights by users
       Manage buying and selling orders for users with off-chain (out of block chain)
    - Transaction processing on on-chain
       Secure Smart Contract that can handle transactions established on-chain
       Example) ⇒ Smart contracts provided by the 0x protocol
    - Distributed Order Book (order board)


### 2-2. Development technology of DEX (Distributed Exchange)

**About Distributed Application (Dapp)  
Case Study: How 0x (zero · X) works**
DEX protocol to trade different tokens (Maker ⇔ Taker) in an Ethernet block chain
protocol: a lots of DEX was built on the 0x
Goal:**DEX transactions scale, fast trading, low transaction fee**


### 2-3. Development technology of DEX (Distributed Exchange)

![11](https://user-images.githubusercontent.com/12098113/48249675-2d5de180-e43f-11e8-8df0-558f7e046ab5.png)

① Maker approves the token M of the Maker's account on the block chain of the Enterprise so that the DEX contract can access it

② The Maker orders the transaction to exchange its own token M with the token T. At this time, the signature is done with Maker's private key

③ Maker broadcasts this trading order to the network

④Taker receives the trading order

⑤ Taker approves the token T of the Taker's account on the block chain of the Enterprise so that the DEX contract can access it

⑥ Taker presents Maker's signature to DEX contract (* 1)
⑦DEX contract (* 1) performs transaction settlement of token M and token T
* 1: Smart contract: automatic settlement


### 2-4. Development technology of DEX (Distributed Exchange)

![12](https://user-images.githubusercontent.com/12098113/48249678-30f16880-e43f-11e8-8a40-60e9fa1ad412.png)

①Relayer presents the address to receive the estimate of transaction fee and the commission to Maker

② The Maker makes a trading order and sets the presented transaction fee. At this time sign it with Maker's private key

③ Maker presents signed order to Relayer

④Relayer checks whether the received order is valid or not and records it in Order Book if valid

⑤Taker receives the OrderBook whose Maker's order has been updated

⑥Taker finds the order you wish to trade and presents it to the DEX contract of the block chain of the EOS


### 3. Difference in issuance of tokens between Eos base and Ethernet basis

![13](https://user-images.githubusercontent.com/12098113/48249681-32bb2c00-e43f-11e8-9bf8-143f426974fa.png)


### 4. Infrastructure diagram of DEX (Distributed Exchange)

![14](https://user-images.githubusercontent.com/12098113/48249685-351d8600-e43f-11e8-9acd-df90aabecfa4.png)


**At i8 exchanges, we are making hybrid exchanges that can take advantage of advantages while compensating for the disadvantages of DEX and CEX (DEX with EOS block-chain)**

**The features of the i8 exchange** are as follows

![2](https://user-images.githubusercontent.com/12098113/48248863-6052a600-e43c-11e8-866a-36096324e2e9.png)

• Form an aggregated order queue based on data received from all system nodes (both CEX and DEX nodes).

• Route the aggregated queue order to the block chain network.

• we can use ordering with offline

• Identification of the system node when it is necessary to transmit the order / transaction submitted by the customer (when it is possible to make a transaction at the price specified in the order)

• Include orders in the block chain.

• Receive information on matching results.
Note: Since the entire I8 exchange system does not have an adequate price, orders that can not be executed at the time of being displayed are described in the node.
Essentially, each node of the I8 exchange provides users with the best executive services that are obligatory for intermediaries in most countries with developed financial markets.

![default](https://user-images.githubusercontent.com/12098113/48248871-66488700-e43c-11e8-8c07-849bc3561990.png)

In addition, such an approach requires that each exchange have an obligation to send orders submitted by customers to another exchange where the latest best price may exist (cross-chain) basis of the domestic market system . A smart order router module operating on each network node (including CEX) is responsible for the function of the best executive in the system.

![1](https://user-images.githubusercontent.com/12098113/48248876-68aae100-e43c-11e8-837f-9731b1cfaafa.png)

The appropriate architecture at the CEX assumes the creation of a modular system containing isolated (logically) blocks, which associates the two main layers of the system (CEX / DEX). 
