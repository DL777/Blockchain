![Axelar](Axelar.png)
# Case Study: Axelar
## What Is It

Axelar is Toronto/Waterloo based company providing a decentralized network that connects dApp builders with blockchain ecosystems, applications and users for frictionless cross-chain communication.  

Axelar consists of a protocol suite, tools, and APIs, designed to break down the barriers to cross-chain communication. Powered by a decentralized open network of validators; anyone can join the network, use it and build on it. 

The **Axelar Fabric** provides a uniform solution to cross-chain communication that meets the needs of both platform developers and application builders. For platform developers no integration work is required from them, and for application builders one simple protocol and API can be used to access global liquidity and communicate with the entire ecosystem. 

By building the infrastructure that is currently missing from blockchain cross-chain solutions, Axelar is making cross-chain communication as simple as using the internet. Developed by the founding team members of Algorand, Axelar’s co-founders are award winning graduates of MIT, where they received notable recognition as part of their graduate studies. Among Axelar’s backers include Binance X, DCVC, Lemniscap, Collab+Currency, North Island Ventures, Divergence Ventures, Cygni Labs among others.

## Why This Matters

Blockchain systems are quickly gaining popularity and attract new use cases for asset tokenization, decentralized finance, and other distributed applications. Several major platforms such as Ethereum, Monero, EOS, Cardano, Terra, Cosmos, Avalanche, Algorand, Near, Celo, and Polkadot offer distinct features and development environments that make them attractive for different applications, use-cases, and end-users.

However, the useful features of each new platform are currently offered to less than 1% of the ecosystem’s users, namely the holders of the native token on that platform. 

## Axelar’s Solution
To bridge the blockchain ecosystems and enable applications to communicate frictionlessly across them, Axelar proposes their own eponymous network. In Axelar network, Validators collectively run a byzantine consensus protocol and run the protocols facilitating cross-chain requests. Anyone can join the network, participate, and use it. The underlying network is optimized for high safety and liveness requirements unique for cross-chain requests. Axelar network also includes a protocol suite and APIs. 

The core protocols are: 

•	**Cross-Chain Gateway Protocol (CGP).** This protocol is used to connect multiple autonomous blockchain ecosystems and is responsible for routing across them. Blockchains do not need to “speak any custom language”, their platform developers do not need to make any custom changes on their chains, and their chains can be plugged into the global network easily. 

•	**Cross-Chain Transfer Protocol (CTP).** This protocol is analogous to application-level protocols File Transfer, Hypertext Transfer Protocols on the Internet. It is an application-level protocol stack that sits on top of routing protocols (such as CGP and other routing technologies). Application developers can connect their dapps on any chain to perform cross-chain requests. Users can use the CTP protocol to interact with applications on any chain using simple API calls analogous to HTTP GET/POST requests. Developers can lock, unlock, and transfer assets between any two addresses across any blockchain platforms, execute cross-chain application triggers (e.g., an dapps on chain A, can update 1 its state if some other application on chain B satisfies some search criteria (interest rate > X)), and perform general cross-chain requests between apps across chains (a smart contract on chain A can call to update a state of a smart contract on chain B). This protocol enables the composability of programs across blockchain ecosystems. 

Axelar network offers the following advantages: 

•	**For blockchain platform builders**: Ability to easily plug-in their blockchains to all other blockchain ecosystems. Only a threshold account needs to be set up on the chain to plug into the network. 

•	**For dapps builders**: Application builders can host their dapps anywhere, lock, unlock, transfer assets, and communicate with applications on any other chain via CTP API. 

•	**For users**: Users can interact with all applications across the ecosystem directly from their wallets. 

Finally, Axelar network is a platform for developers and a global community. Its governance model is open to anyone. Developers can propose new integration points, routing, and application-level protocols, and the users can decide whether to adopt them by voting on the proposals and, if approved, validators will adopt the changes.

# Existing Interoperability Solutions

Previous attempts to solve interoperability across blockchains fall in one of four categories: centralized exchanges, interoperable ecosystems, wrapped assets, and token bridges.

The existing solutions for interoperability require heavy engineering work from both platform developers and application builders that must understand different communication protocols to communicate across every pair of ecosystems. And so, interoperability is virtually non-existing in today’s blockchain space. At the end of the day, platform developers want to focus on building platforms and optimize them for their use-cases and be able to plug in to other blockchains easily. And application developers want to build dapps on the best platforms for their needs while still leveraging users, liquidity and communicate with other dapps on other chains.

# Axelar Network
Axelar network consists of a decentralized network which bridges blockchain ecosystems that speak different languages and a protocol suite with APIs on top, making it easy for applications to perform cross-chain requests. The network connects existing stand-alone blockchains such as Bitcoin, Stellar, Terra, Algorand, and interoperability hubs such as solutions like Cosmos, Avalanche, Ethereum, and Polkadot.

A core component of the network are the underlying decentralized protocols. Validators collectively maintain the Axelar network and run the nodes that secure the Axelar blockchain. They are elected through a delegation process by the users. Validators receive voting power pro-rata according to the stake delegated to them. The validators reach consensus on the state of multiple blockchains that the platform is connected to. The blockchain is responsible for maintaining and running the cross-chain routing and transfer protocols. Governance rules allow network participants to enact protocol decisions such as which blockchains to bridge and which assets to support.

Axelar blockchain follows a **Delegated Proof-of-Stake (DPoS)** model similar to Cosmos Hub. Users elect validators who must bond their stake to participate in the consensus and maintain high-quality service. The DPoS model allows maintenance of large decentralized validator set and robust incentives to guarantee that the validators are responsible for maintaining bridges and shares of cryptographic threshold schemes. As part of consensus, validators run light-client software of other blockchains, allowing them to verify the state of other blockchains. The validators report these states to the Axelar blockchain, and once enough of them report, the state of Bitcoin, Ethereum, and other chains is recorded on Axelar.

Subsequently, the Axelar base layer is aware of the state of external blockchains at any point in time, creating the “incoming bridges” from other blockchains. The validators collectively maintain threshold signature accounts on other blockchains (e.g., 80% of validators must approve and co-sign any transaction out of it), which allows them to lock and unlock assets and state across chains and to post state on other blockchains, the “outgoing bridges.” Altogether, one can view the Axelar network as a decentralized crosschain read/write oracle. 

# Seed Funding
In November 2020, Axelar raised $3.75 million in seed funding. The funding round included participation from investors including Binance X, the investment arm and accelerator of cryptocurrency exchange Binance, as well as San Francisco-based venture capital firm DCVC (Data Collective).

Other participants included crypto investment firm Lemniscap, crypto operator fund Divergence Ventures, serial entrepreneur Waikit Lau and AngelList founder Naval Ravikant.


# Resources

1. Axelar Whitepaper. (2021, January). Axelar Network: Connecting Applications with Blockchain Ecosystems https://static1.squarespace.com/static/5f7679246f2afb311bbb67dd/t/602d3503ad35b40d1bdc209c/1613575428020/axelar_whitepaper_v1.pdf
2. Gorbunov, S. (2020, November 19). Why Blockchain Interoperability is just a Buzzword. Medium. https://medium.com/axelar/why-blockchain-interoperability-is-just-a-buzzword-4e3f17698c1
3. Gorbunov, S. (2021, January 6). The Foundation of Cross-Chain Communication. Medium. https://medium.com/axelar/the-foundation-of-cross-chain-communication-291f5a4f9879
4. Gorbunov, S. (2021, February 17). Introducing Axelar Network. Medium. https://medium.com/axelar/introducing-axelar-network-45fccea94730
5. Sinclair, S. (2020, November 13). Algorand-Linked Axelar Raises $3.75M in Seed Funding to Help Blockchains Communicate. Coindesk. https://www.coindesk.com/alogrand-alumni-protocol-seed-funding

