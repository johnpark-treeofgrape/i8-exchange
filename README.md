# i8-exchange
I8 is HEX(Hybrid Exchange) with EOS blockchain


**[homepage](http://www.i8exchange.com/)**



## 1.Security of DEX (Distributed Exchange) (including reliability and transparency)

- USER ASSET MANAGEMENT: There is no need to deposit assets

- TRUSTRESS: There is no need to trust an exchange (run away, risk of hacking is low)
⇒ "Trustless" is the characteristic of the block chain (trust is unnecessary for a third party).
⇒ There is little fear of hacking in storage or transactions
⇒ It is unlikely that personal assets will be lost due to the malice of others (there is little chance that regulation will take place as fraud is unlikely to occur)

- P2P: Since it is a relative transaction between customers, security is strong enough

- NoManager: Since there is no administrator, there is no need to send passwords or personal information to exchanges

- Fully Decentralized: Identity verification procedure, login etc. unnecessary (safety + easy to register)

- smart contract: encrypted and distributed among nodes. Specifically, this guarantees that it will not be lost or changed without your permission

- Each node with server: effect of down for infraction is limited (Reliability)


### 2-1. Development technology of DEX (Distributed Exchange)

Next Generation Virtual Currency / Encryption Currency Exchange System = Distributed Application (Dapp)

* Used to buy and sell ERC 20/EOS tokens based on Ethereu/EOS (Ethereum/EOS)

* There are something which incorporate some centralized system to speed up the process

* There are something without Order Book

* System configuration
- Maintain asset management rights by users
       Manage buying and selling orders for users with off-chain (out of block chain)
    - Transaction processing on on-chain
       Secure Smart Contract that can handle transactions established on-chain
       Example) ⇒ Smart contracts provided by the 0x protocol
    - Distributed Order Book (order board)


### 2-2. Development technology of DEX (0x)

**About Distributed Application (Dapp)  
Case Study: How 0x (zero · X) works**
DEX protocol to trade different tokens (Maker ⇔ Taker) in an Ethernet block chain
protocol: a lots of DEX was built on the 0x
Goal:**DEX transactions scale, fast trading, low transaction fee**


### 2-3. Detail of technology of DEX (ETH)

![97d4f1e6cd4ad9335a51e9e30c7ffbed](https://user-images.githubusercontent.com/12098113/50539983-a9b5ab00-0bcc-11e9-975e-f82177a19b46.png)


① Maker approves the token M of the Maker's account on the block chain of the Enterprise so that the DEX contract can access it

② The Maker orders the transaction to exchange its own token M with the token T. At this time, the signature is done with Maker's private key

③ Maker broadcasts this trading order to the network

④Taker receives the trading order

⑤ Taker approves the token T of the Taker's account on the block chain of the Enterprise so that the DEX contract can access it

⑥ Taker presents Maker's signature to DEX contract (* 1)
⑦DEX contract (* 1) performs transaction settlement of token M and token T
* 1: Smart contract: automatic settlement


### 2-4. Development technology of DEX (EOS)

![60643d751400684153631eb5d15e23d8](https://user-images.githubusercontent.com/12098113/50540046-edf57b00-0bcd-11e9-85aa-232099777581.png)


① Relayer presents the address to receive the estimate of transaction fee and the commission to Maker

② The Maker makes a trading order and sets the presented transaction fee. At this time sign it with Maker's private key

③ Maker presents signed order to Relayer

④Relayer checks whether the received order is valid or not and records it in Order Book if valid

⑤Taker receives the OrderBook whose Maker's order has been updated

⑥Taker finds the order you wish to trade and presents it to the DEX contract of the block chain of the EOS

### 3. i8 Exchange Plan
i8 Exchange plans to offer digital asset spot trading, CFD trading and on-chain trading. i8 exchange.
An exchange token called the IE token (i8 exchange proof). When an IE token is issued, the i8 exchange is no longer an independent block-chain entity, but a distributed company managed by the community.
IE Token Holder and i8 Exchange Foundation. All IE token holders share the profits generated from the i8 exchange. As a result, i8 Exchange will be a community-based platform that works with all members and partners to build a global one-stop platform for quality digital assets.

### 3-1. CFD Trading
i8 Exchange supports in-kind transactions of cryptocurrencies. As the platform develops and trading volume becomes more secure and reliable, CFD trading begins. When this happens, the range of products that can be traded on the i8 exchange will be greatly expanded. cryptocurrencies, equity, foreign exchange, and commodities-i8 exchange will be a global one-stop shop for truly transaction-quality digital assets. Of course this would be interpreted as a tremendous benefit to the i8 exchange platform shared among IE token holders, creating a strong and steady passive income for all IE token holders

### 3-2. On Chain Trading
EOS represents a mature, fast transaction, low-latency technology and attracts the best developers. In the summer of 2018, we saw numerous game projects, gambling projects and Bancor transactions leading to the EOS platform. We have little doubt that the next wave of dApps will bring another exciting group of entrants. On the other hand, CPU, Net and RAM prices are still high, but the barriers to opening EOS accounts are somewhat burdensome, but they will provide on-chain transactions in a way that provides fast and secure access to on-chain services.

### 3-2-1. On Chain Trading Model
Our unique trading model not only allows you to exchange between different assets internally within your account with an i8 exchange but also allows you to deposit a minimum amount of EOS and have full access to all the EOS related services you do not need. .

### 3-3. Platform Revenue Sources
1.Trading Fees: 0.02%

2.Overnight Carrying Charge on CFDs:Undecided

3.On-chain transfer fee: 0.02%

4.Withdrawal Fees (Undecided)






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


### 4. Security
The "Know Your Customer" (KYC) process is a very important step that allows I8 to reduce curtail malicious intentions and acts and to identify the individuals who intend such acts. With this ID recognition process, I8EXCHANGE can also monitor and limit the number of master nodes that an individual maintains. This prevents one individual from becoming the majority owner of the master node and can control and control the network exclusively.

In addition to the KYC process, checking and balancing within the node hierarchy also increases the security level within the platform. If the monitored master node maliciously detects the master node in the system, the suspicious MN is excluded from the system and its activities and permissions are suspended. After investigating, the owner of the accused master node loses the locked up token and may not be able to build a master node in the future. This provides a very strong deterrent to malignant people trying to join the I8 environment.
For more detailed information on other security measures implemented on the I8 platform.

### 4-1. PoC
PoC is a new consensus building algorithm that makes high speed and high security compatible. PoC solves the current challenges of existing protocols such as slow block time, low transaction speed and low scalability while maintaining fairness of data distribution, zero downtime and anti-counterfeiting measures.
PoC has significant advantages over other block chain platforms.
- 0.3 seconds Block time:
    - Omission of nonce bypasses arithmetic processing, and shortens processing time dramatically
    - High-speed block generation is possible by node hierarchy and role sharing
- Scalability:A flexible network structure allows an unchanging user experience during times of high traffic
    - The number of master nodes and super nodes increases or decreases according to network traffic
- Uniform information distribution:
    - Even when dealing with large-scale PoC global networks, information is delivered in exactly the same way.
- Approval of transactions by permutation
- Process optimization by assigning roles using the node hierarchy
- Construction of a proprietary network that efficiently distributes information Coupled with these unique features, we are constructing an ultra-fast and secure network configuration.

### 5. Smart Transaction Matching Engine
Transactional inefficiency of decentralized trading is triggered by a request that customers must be put in a block chain while waiting for the pairing to succeed. The user can only wait passively for the counterparty having the equivalent transaction amount.   If the transaction quantity is different, you can complete only a part of the transaction first. Thereafter, the user must make another order manually to sell the remaining digital currency. On the contrary, I8 actively supports users of off-chain smart pairing using its smart transaction matching engine. When a user initiates an order using a cryptographic signature, the order information is sent to the I8 matching engine before it is listed in the order book of the I8 trading platform. The I8 Smart Transaction Matching Engine actively checks the supply and demand of the order pool on a first-come-first-served basis and only checks with orders with prices below the predefined cost. In addition, the orderer can also manually select favorite orders from the order book on the I8 exchange platform. Smart pairing is done outside the chain, but all movements are made public on the exchange platform to ensure transparency. If pairing is successful, I8 will initiate a smart contract with cryptographic signatures from both the order maker and the block chain. When transaction confirmation is completed in the block chain, the system issues a broadcast and the digital currency is exchanged accordingly. This mechanism means that digital currency transfers can only occur between individual users and not on I8 exchanges. If there is no cryptographic signature from the user, the transaction will not be treated as valid, nor sent to the block chain or confirmed.

![default](https://user-images.githubusercontent.com/12098113/48248871-66488700-e43c-11e8-8c07-849bc3561990.png)

**approach requires that each exchange have an obligation to send orders submitted by customers to another exchange where the latest best price may exist (cross-chain) basis of the domestic market system . A smart order router module operating on each network node (including CEX) is responsible for the function of the best executive in the system.The appropriate architecture at the CEX assumes the creation of a modular system containing isolated (logically) blocks, which associates the two main layers of the system (CEX / DEX).**

![1](https://user-images.githubusercontent.com/12098113/48248876-68aae100-e43c-11e8-837f-9731b1cfaafa.png)

