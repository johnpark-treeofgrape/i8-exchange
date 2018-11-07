# i8-exchange
this is HEX(Hybrid Exchange) with EOS blockchain

[technical white-paper](https://www.google.co.jp/)







## Security of 1-1DEX (Distributed Exchange) (including reliability and transparency)

- USER ASSET MANAGEMENT: There is no need to deposit assets

- TRUSTRESS: There is no need to trust an exchange (run away, risk of hacking is low)
⇒ "Trustless" which is the characteristic of the block chain (trust is unnecessary for a third party) can be realized
⇒ There is little fear of hacking in storage or transactions
⇒ It is unlikely that personal assets will be lost due to the malice of others (there is little chance that regulation will take place as fraud is unlikely to occur)

- P2P: Since it is a relative transaction between individuals and individuals, security is strong

- NoManager: Since there is no administrator, there is no need to send passwords or personal information to exchanges.

- Fully Decentralized: Identity verification procedure, login etc. unnecessary (safety + easy to register)

- smart contract: The transaction record remains by the automatic contract, the transaction history. (transparency)

- Each node with server: Influence down effect is limited (Reliability)


### 2-1. Development technology of DEX (Distributed Exchange)

Next Generation Virtual Currency / Encryption Currency Exchange System = Distributed Application (Dapp)

* Used to buy and sell ERC 20 tokens based on Ethereum (Ethereum)

* There are some which incorporate some centralized system to speed up the process.

* There are things without Order Book

* System configuration
- Maintain asset management rights by users
       Manage buying and selling orders for users with off-chain (out of block chain)
    - Transaction processing on on chain
       Secure Smart Contract that can handle transactions established on-chain
       Example) ⇒ Smart contracts provided by the 0x protocol
    - Distributed Order Book (order board)


### 2-2. Development technology of DEX (Distributed Exchange)

**About Distributed Application (Dapp)  
Case Study: How 0x (zero · X) works**
Different tokens (Maker ⇔ Taker) in an Ethernet block chain with DEX protocol to trade to Various DEX applications are created on platform: 0x to the last.
Goal:**DEX transactions scale, fast trading, low transaction fee**


### 2-3. Development technology of DEX (Distributed Exchange)


① Maker approves the token M of the Maker's account on the block chain of the Enterprise so that the DEX contract can access it

② The Maker orders the transaction to exchange its own token M with the token T. At this time, the signature is done with Maker's private key

③ Maker broadcasts this trading order to the network
④Taker receives the trading order

⑤ Taker approves the token T of the Taker's account on the block chain of the Enterprise so that the DEX contract can access it

⑥ Taker presents Maker's signature to DEX contract (* 1)
⑦DEX contract (* 1) performs transaction settlement of token M and token T
* 1: Smart contract: automatic settlement



**At i8 exchanges, we are making hybrid exchanges that can take advantage of advantages while compensating for the disadvantages of DEX and CEX**

**The features of the i8 exchange** are as follows
